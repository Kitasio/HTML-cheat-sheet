# Hyper Text Markup Language

HTML is not a programming language, meaning it's strictly presentational and there's no logic magic here

the simple format of every page looks like this:

```
<!DOCTYPE html>
<html>
	<head>
		<title>HTML cheat sheet</title>
	</head>	
	<body>
		<!-- Comment -->
		<h1>Heading</h1>
	</body>
</html>
```
## Tags

Inline elements: `<span>`, `<img>`, `<a>`...)
- Do not start with a new line
- Take only the necessary width

Block elements: (`<div>`, `<h1>`, `<p>`, `<form>`...)
- Start with a new line
- Take full width avaliable

There are 6 heading types h1 - h6 (h1 is the biggest)

`<strong>` - Is a sementic tag to make text stick out, by default will be bold

`<em>` - will make the text itallic

but they both can be changed with css

`<a href="http://google.com" target="_blank"> The link text </a>`

- `a` - the tag of the link
- `href` - site or plase to link to
- `target="_blank "` - to open link in a new tab (if you do external link)

href is an attribute, they work in a key = value strcture and placed in the opening tag

### Lists

`<ul>` - is an unorderd list
`<ol>` - ordered list
`<li>` - is for the text inside the list

### Table

`<table>` - creates... tables
`<thead>` - here we usually put names, open a `<tr>`, and every name wrapped in `<th>`
`<tbody>` - here is the data under the name, open `<tr>`, and here we use `<td>` for the data

### Forms

Forms are used for login templates and things like that

Note that its only the look of it, the form is actually dead man...

`<form>` - the form tag, every tage below goes inside the form tag
`<label>` - for the label
input example: `<input type="text" name="firstName">` (you can use type="email" for email validation, there are also `"date"` types, `"number"` types,`"submit"` for the button inside the form, etc...)
`<textarea name="message">` - is another tag for bigger field
`<select>` - for choice and it take `<option value="something">` tag inside
 
### Button

`<button>` - in order for it to do something - you need javascript

### Image

`<img>` - to load the image you need the attribute `src`, attribute `alt` is used to describe the image if for some reason it doesn't load, also note `width` and `height`

### Quotes

`<blockquote>` - is used if you want to quote someone, put `cite` inside to reference to a source

`<abbr title="bla bla bla">BBB</abbr>` - cool little thing for abbreviations 

## Semantic Tags

```
<header></header>
<footer></footer>
<aside></aside>
<main></main>
<article></article>
<nav></nav>
<section></section>
<details></details>
```

also `meta` tag is placed in the header, put there description and some key word, so when google scans your website - it looks there
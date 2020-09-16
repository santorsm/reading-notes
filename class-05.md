# Style Web Pages with CSS

## New Vocabulary

- CSS - associates rules with HTML elements
  - made of two parts: selector (ex. `p`) & a declartion (ex {`font-family:` `Arial;`})
- RGB - rgb(100,100,90)
- HSL
- Hex codes - amount of `red`, `green1, and `blue` in a color
- Layout
- Rule - grouping to 1or more properties applied to 1 or more properties
- Selector - selecting from HTML what to effect
- Property & value - *property:value* similar to key value pair 
- Curly braces -  { at the beginning and } at the end 

- **selectors** on p238

### Block & Inline elements:
- **Block** **level** elements look like they start on a new line
  - Examples include the `<h1>`, `<h6>`, `<p>` and `<div>` elements
- **Inline** flow within the text and do not start on a new line
  - Examples include `<b>`, `<i>`, `<img>`, `<em>` and `<span>`

### Using External CSS
- `<link>` : tells brwser where to find CSS doc
  - empty element - no need for closing tag
  - lives inside the `<head>` element
  - 3 attributes:
    - `href`: specifies the path to CSS file
    - `type`: the type of document being linked to
    - `rel`: specifies the relationship between HTML page & file its linked to
      - `stylesheet` for CSS file
- can have more than one CSS file
  - one for controlling *presentation*
  - one for conrollling the *layout* 
# Markdown Basics

## Headlines, Paragraphs, and Basic Formatting

### Headlines

Type a single hash (AKA pound symbol) and a space to create the largest or first-level heading. A second-level heading uses two hashes next to each other followed by a space and text. The rest of the headline levels just add another hash.

#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

### Paragraphs and Line Breaks

We create paragraphs by typing the way we would in any other program. Just hit return twice to start another paragraph.

Where you see empty space between blocks of text in your Markdown document, you will see empty space separating those blocks of text in your formatted HTML document.

#### Line Breaks

You don’t always want that space that appears between one line of text and another: for example, lines of poetry or song lyrics don't have spaces between them. To add just a line break without a space, type two spaces at the end of a line, then press return once.

I love you without knowing how, or when, or  
from where  
I love you directly without problems or pride:  
I love you like this because I don't know any  
other way to love     

Neruda, Pablo. "Sonnet 17" The Poetry of Pablo Neruda, edited by Ilan Stavans, translated by Mark Eisner, Farrar, Straus and Giroux, 2005, p. 514.

### Emphasis and Bolding

#### Italics

Emphasis can be added with either the asterisk or the underscore characters.

This *works*, and this _works_ too

#### Bolding

Bolding is easy too. Just add an extra asterisk or underscore.

This **works**, and this __works__ too

#### Bolding and Emphasis Together

You can even bold and italicize text like ***this*** or ___this___

### Blockquotes

A blockquote sets text apart from the rest of the document. It indicates that the text is quoted from another source.

You format a blockquote using the greater than symbol. If you want a blockquote to span multiple paragraphs, add the greater than symbol to the line between paragraphs too.

> Markdown is intended to be as easy-to-read and easy-to-write as is feasible.
>
> Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions. — [John Gruber](https://daringfireball.net/projects/markdown/ "The Creator of Markdown")

### Horizontal Rule

OK, that’s a good start. We can separate this from our next section with a horizontal rule, which is just a line used to separate sections of a document.

You can use three or more underscores, asterisks, or hyphens. I prefer hyphens.

___

***

---

## Lists

You can write both numbered and bulleted lists with Markdown.

### Numbered Lists

You create numbered lists like you do in other writing programs. Type the number, a period, a space, and the item label.

1. Item One
2. Item Two

To nest an item, indent it with a tab or at least two spaces beneath the item above it.

1. Item One
    1. Nested Level Two
    2. Nested Level Two
        1. Nested Level Three
        2. Nested Level Three

#### Bulleted Lists

Bulleted lists work like numbered lists, but you use the asterisk character, a space, and no period.

* Item One
* Item Two

You can nest bulleted items too. We just indent our item below another item like we did with our numbered list.

* Item One
    * Nested Item One
    * Nested Item Two

##### Asterisk Gotchas

Because the asterisk is used for bolding, italicizing, and creating bulleted lists, it's easy to make mistakes. Check your spacing, and use a preview to ensure you are formatting text the way you intend.

*Italicized Item*  
*Not Formatted
* Bulleted Item

What if you do want a bulleted item that is bold and italicized? Type an asterisk and a space. This will create the bulleted item. Then use two asterisks for the bolding and a third for the italicizing on both sides of the text.

* ***Bold Italicized Bulleted Item***

#### Mixed Lists

You can mix the two list styles too. Just use the numbers or asterisks where you want them.

1. Item One
    * Nested Item
    * Nested Item
2. Item Two
    * Nested Item
    * Nested Item
        1. Deep Nested Item One
        2. Deep Nested Item Two
            * Super Deep Nested Item
            * Super Deep Nested Item

---

## Code

We format code using the backtick character. The backtick is on the same key as the tilde on a U.S. English keyboard, which is usually to the left of the number 1 and above the tab key.

You can use a single backtick to create inline code. For example, you may type something like this:

To install the latest version of NPM, you can type,  `npm install npm@latest -g`

For multiple lines of code, you'll usually create a code block. Instead of one backtick, use three backticks above and below the code block. Some sites and editors also support syntax highlighting by language. Add it by typing the name of the coding language immediately after the top three backticks.

```JavaScript
let exampleFunction = () => {
  let foo = 'foo';
  let bar = 'bar';

  return foo + bar;
}
```

---

## Links

Markdown provides a syntax for links that’s easy to remember. First, type the text you want to appear on the page in square brackets, then add the link in parenthesis. If I want to link to Treehouse, I would type

[Treehouse](https://teamtreehouse.com/)

You also have the option to provide a title, which appears when you hover the mouse cursor over the link. Just type a space after the url and close the label in quotes. Both the url and the title should be inside the parenthesis.

[Treehouse](https://teamtreehouse.com/ "Treehouse link with a title")

What if you want to link to a reference at the bottom of a section or page like a footnote? Start with the text in square brackets, but don’t add the parenthesis. Instead, add a number to reference in another set of square brackets.

[Treehouse][1]

Now at another place in the document, add the reference number in square brackets and follow it with a colon, a space, and the link url. You can add an optional title with a space and quotes to this type of link too. Reference links don’t require parenthesis.

[1]: https://teamtreehouse.com "Treehouse Reference Link"

---

## Images

Type a label for the image in square brackets. On the Web we call this alt text, because it will be displayed as an alternate if the image cannot be shown for any reason. I have an image of kittens, so I’ll write, “Kittens” in square brackets and follow that with the url for the image in parenthesis.

That creates a link for the kitten image, but I want to display the image. All I have to do is add an exclamation mark in front of the square brackets.

![Kittens](https://placekitten.com/250/400)

What if I want the image to link to something too? Just add square brackets around your whole image code. At the end of the new square brackets, put the link url in parenthesis.

[![Kittens](https://placekitten.com/300/400 "Fluffy Kitten")](https://placekitten.com)

Images can have titles like links too. You add them the same way. After the image url, add a space and put the title in quotes.

[![Kittens](https://placekitten.com/350/400 "Curious Kitten")](https://placekitten.com)

---

## Conclusion

That's it for this document. You now have a handy Markdown reference. Feel free to explore more information about Markdown and its many flavors, but this is a great start. The more you use Markdown the more natural it will feel.

Thanks for learning Markdown with [Treehouse](https://teamtreehouse.com "Treehouse")

# Basic Markdown Syntax

This is a paragraph under the level one heading. Don't use more than one level one heading, because search enginges prioritize it. When using Pandoc you will not even need a level one heading because the `Title` is better placed in the meta-data property instead and rendered with the Pandoc Template (I am not sure if I will follow that advice). 

This is another paragraph. Make your paragraphs just a single long line and don't do something horrible like newlines every 80 characters. It will wrap terribly on different screen sizes and make reading much harder than necessary. 

**Also every programming project should have a README.md**

All of this is shamelessly taken from [\<rwx.gg\>](https://duckduckgo.com/?q=basic+markdown+rwx.gg+rwxrob).


## Headings

Headings (often incorrectly called headers) begin with 1 - 6 hashtags / octothorpes (`#`) followed by space and then the title text followed by a single blank line. 

~~~markdown
# Level One
Paragraphs and such here.

## Level Two
Paragraphs and such here.
~~~


## Formating

One star for *italics*.

Two stars for **bold**.

Three stars for ***bold italics***.

Backticks for `monospaced`.

Dont use the _ underscore. It will create problems later on...


## Links / Hyperlinks

Hyperlinks (stuff you click on) come in three basic forms:

1. Words
1. URLs
1. Images

### Hyperlinked Words

The most common link in markdown is just words you can click on that take you to local places or external sites. The web address must be either pointing to a remote site or to something on the same site that document is on.

Here is a [link to Wikipedia](https://www.wikipedia.org/).

Code:

`Here is a [link to Wikipedia/](https://www.wikipedia.org/).`

Is is also nice to mark links that lead to external sites. You could, for example, use `< >` to easily distinguish external links. 

Here is a [\<link to Wikipedia\>](https://www.wikipedia.org/).


### Autolinked URLs
Sometimes you want to show the full web address. Here is the URL to <https://www.wikipedia.org/> that will appear in full.

Code:
`Here is the URL to <https://www.wikipedia.org/> that will appear in full.`

This also works with other link types besides http:

* Mail me at <mailto:test@someemail.com>
* Phone me at <tel:+49111-23456789>


## Images
Images are just links with an exclamation point in front. Make sure to put a blank line before and after any image for maximum compatibility. Inline images are not widely supported an mess up other formatting in almost all cases.

`![Nethack](img/Nethack-kernigh-22oct2005-80.png)`

Images can also be used as links:

`[![Nethack](img/Nethack-kernigh-22oct2005-80.png)](https://commons.wikimedia.org/w/index.php?title=File:Nethack-kernigh-22oct2005-80.png)`

And in use:
[![Nethack](img/Nethack-kernigh-22oct2005-80.png)](https://commons.wikimedia.org/w/index.php?title=File:Nethack-kernigh-22oct2005-80.png)`



This is a descriptive README file of all the important hacks in Markdown.
------------------------------------------------------------------------
Headers
------------------------------------------------------------------------
# HEADER ONE
## HEADER TWO
### HEADER THREE
------------------------------------------------------------------------
Links
------------------------------------------------------------------------
Enclose links in the () tags and use a placeholder text in square brackets [] right before it.
[Stackoverflow](www.stackoverflow.com)

You can also store your link as a variable and call it elsewhere in your file.

The most widely used search engine in the world is [Google]

-------------------------------------------------------------------------
Emphasis
-------------------------------------------------------------------------
**Italics**

Wrap text in between a pair of astersiks `*` or underscores `_`
I am learning how to code at 6 am in the _freezing morning_. Though I am rather *pleased*.

**Bolden**

You can make words bolder by using two pairs of asterisks or underscores.
Some popular programming languages include **Python**, **Java**, **C#**, and **Ruby**

-------------------------------------------------------------------------
Code
-------------------------------------------------------------------------
To insert a line of code in your documentation, wrap it around a **single backtick** on either side of the codeline.
For a larger block of code, wrap it using **three backticks (```)** on both ends of your codeblock.

`var applePrice = 80`

```
   if age <= 17:
	person = "Child"
   else:
	person = "Adult"
```

*You can also indent each line of the codeblock with four spaces*

--------------------------------------------------------------------------
Math Expressions
--------------------------------------------------------------------------

Markdown uses LaTex symbols.

These can be used to render math symbols and expressions.

To start math mode in Jupyter Notebooks, wrap the LaTex in dollar sign.

` $ y =mx+ b $ `

For blocks of Math expressions, you can use $$ two dollars signs wrapped at the top and bottom of the expression:

$$
y = /fract {a}{b}
$$

---------------------------------------------------------------------------
Strikethrough
---------------------------------------------------------------------------

We use **two tildes** to strikethrough text. `~~`
~~ Scratch this~~

---------------------------------------------------------------------------
Blockquotes
---------------------------------------------------------------------------
Start a line with the > greater than symbol
They can be nested

>Today is the 13th of June 2022, the cold season has set in and shoppers will be flooding malls to buy the their warm gear.
> Westgate Mall should expect an influx of customers during this month.

---------------------------------------------------------------------------
Lists (yeah this shoud have come way sooner at the top)
---------------------------------------------------------------------------
Lists in Markdown are annotated like any other word processor, only there's a catch. You can bypass having to name
each line with it's concurrent number.

You could simply use the number 1 for every time and MD would automatically render the list.

There are ten teams in Formula 1:
1. Williams
1. Ferrari
1. Alfa Romeo
1. Red Bull
1. Mercedes AMG-Petronas
1. Mclaren
1. Haas
1. Alpine
1. Alpha Tauri
1. Aston Martin

----------------------------------------------------------------------------
IMAGES
----------------------------------------------------------------------------
The syntax for inserting images in Markdown is : `![alt text]("/image-path" "Title")`

Just like links, images **can also be stored as variables**

----------------------------------------------------------------------------
[Google]: https://www.google.com

----------------------------------------------------------------------------
This has been Markdown in 10 minutes by Tevin Aduma.
Thanks for reading.
----------------------------------------------------------------------------

# How to use syntaxe of Markdown ?

1. [Block Elements](#1-block-elements)  
   1.1 [Paragraphs and Line Break](#11-paragraphs-and-line-break)  
   1.2 [Headers](#12-headers)  
   1.3 [Blockquotes](#13-blockquotes)  
   1.4 [Lists](#14-lists)  
   1.5 [Code Blocks](#15-code-blocks)  
   1.6 [Horizontal Rules](#16-horizontal-rules)  
2. [Span Elements](#2-span-elements)  
   2.1 [Links](#21-links)  
   2.2 [Emphasis](#22-emphasis)  
   2.3 [Code](#23-code)  
   2.4 [Images](#24-images)
3. [Miscellaneous](#3-miscellaneous)  
   3.1 [Backslash Escapes](#31-backslash-escapes)  
   3.2 [Automatic Links](#32-automatic-links)


## **1. Block Elements**


### **1.1 Paragraphs and Line Break**

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs.

The implication of the “one or more consecutive lines of text” rule is that Markdown supports “hard-wrapped” text paragraphs. This differs significantly from most other text-to-HTML formatters (including Movable Type’s “Convert Line Breaks” option) which translate every line break character in a paragraph into a `<br />` tag.

When you do want to insert a `<br />` break tag using Markdown, you end a line with two or more spaces, then type return.

### **1.2 Headers**

Headers go from 1 (the largest) to 6 (the smallest) and are written like this :
  
 * `# H1`<br/> 
 * `## H2`<br/>
 * `### H3` <br/>
 * `#### H4`<br/>
 * `##### H5`<br/>
 * `###### H6`<br/>

  #### Dispayed :

 # H1
 ## H2
 ### H3
 #### H4
 ##### H5
 ###### H6

 *But there is another way to write `# H1` and `## H2` if needed :*

`H1`</br>
`===========`

`H2`</br>
`-----------`

</br>

  #### Dispayed :

H1
===
</br>

H2
---

</br>


 ### **1.3 Blockquotes**

Using for quoting passages of a text, or just quotes someone, the block quotes is usefull.   
For *blockquote* a line, you need to use the "**>**" symbol before your line.  
If you need to blockquote a paragraph with more than **one line**, you have to put the symbol "**>**" before first line of the paragraph.  

**Exemple  :**
>\>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.  
\>  
>\>Lorem ipsum dolor sit amet, consectetur adipiscing elit.

**Render :**  
>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
>
>Lorem ipsum dolor sit amet, consectetur adipiscing elit
  
  ### **1.4 Lists**  
**MarkDown** supports ordered and unordered lists.  
- **Unordered** lists use asterisks(*), pluses(+), and hyphens(-) as list markers:  
   #### Exemple for * : 
   > \* first item  
   > \* second item  
   > \* third item  
   #### Exemple for + : 
   > \+ first item  
   > \+ second item  
   > \+ third item
   #### Exemple for - : 
   > \- first item  
   > \- second item  
   > \- third item
   #### The output: 
   > * first item
   > * second item
   > * third item  

- **Ordered** lists use numbers followed by periods.  
It's important to note that the actual numbers you use does not matter.
   1. #### Exemple for numbers that follow each other :
   > 1. first item 
   > 2. second item
   > 3. third item
   1. #### Exemple for numbers that doesn't follow each other :
   > 5\. fifth item  
   > 8\. sixth item  
   > 10\. seventh item
   #### The output :
   > 5. fifth item  
   > 8. sixth item  
   > 10. seventh item  
   1. #### Exemple if you always use the same number:
   > 1\. first item  
   > 1\. second item  
   > 1\. third item  
   #### The output
   > 1. first item
   > 1. second item
   > 1. third item
   
### **1.5 Code Blocks**
To be able to insert text in HTML, just paste the HTML text and type on TAB

Example:

    <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN">
    <html>
    <head>
    <title>Ma première page avec du style</title>
    </head>
    
    <body>
    
    <!-- Menu de navigation du site -->
    <ul class="navbar">
    <li><a href="index.html">Home page</a>
    <li><a href="reflexions.html">Réflexions</a>
    <li><a href="ville.html">Ma ville</a>
    <li><a href="liens.html">Liens</a>
    </ul>
    
    <!-- Contenu principal -->
    <h1>Ma première page avec du style</h1>
    
    <p>Bienvenue sur ma page avec du style! 
    
    <p>Il lui manque des images, mais au moins, elle a du style. Et elle a desliens, même s'ils ne mènent nulle part...
    &hellip;
    
    <p>Je devrais étayer, mais je ne sais comment encore.
    
    <!-- Signer et dater la page, c'est une question de politesse! -->
    <address>Fait le 5 avril 2004<br>
    par moi.</address>
    
    </body>
    </html>

### **1.6 Horizontal Rules**

You can produce a horizontal rule tag ( `<hr />` ) by placing three or more hyphens, asterisks, or underscores on a line by themselves. If you wish, you may use spaces between the hyphens or asterisks.

## **2. Span Elements**


### **2.1 Links**

You can highlight a word or even a sentence as a link access.
URL's or repositories have adresses that can be linked.
If a URL is not put into braces 

1. `This is [an example](http://example.com/ "Title") inline link.`

2. `[This link](http://example.net/)`
   
3. `[I'm a relative reference to a repository file](../blob/master/LICENSE)`

  #### Dispayed :

1. This is [an example](http://example.com/ "Title") inline link.
   
2. [This link](http://example.net/)

3. [I'm a relative reference to a repository file](../blob/master/LICENSE)

</br> 


### **2.2 Emphasis**


Emphasis in Markdown are very simple.  
To create *italic* or **bold** word or paragraphe, you need to use "**_**" or "__*__" character.   
  
Exemple :  
  >- \_single underscore_ 
  >- \_\_double underscore__  
  >- \*single asterisk*
  >- \*\*double asterisks**

Render :

>- _single underscore_
>- __double underscore__
>- *single asterisk*
>- **double asterisk**

And if you want, you can combine them ! 

So this : 
>\*\*Text \_here_**

Will be :
>**Text _here_**


### **2.3 Code**
To indicate a span of code, wrap it with backtick quotes(\`).  
This is used to indicate code within a normal paragraph.  
- #### Exemple: 
   > Use the `printf()` function.  

If you want to include a literal backtick charachter within a code span,  
you can use multiple backticks as the opeing and closing delimiters.
- #### Exemple: 
   > \`\` There is a backtick here -> ` ``
   #### The output:
   > `` There is a backtick here -> ` `` 

### **2.4 Images**

To insert a still or dynamic image:

   *![sitename]\(linkofthesite) = image which is not clickable


Example:
![Giphy.com](https://media.giphy.com/media/aacdmWnYUMRkk/giphy.gif)

   *[![sitename]\(linkofpicture)]\(linkofthesite) = image which refers to the site

Example: [![Prestashop2.com](https://assets.prestashop2.com/sites/default/files/styles/blog_750x320/public/blog/fr/files/2015/01/7-resources-code-1024x537.png?itok=AXSLDOKg)](https://www.prestashop.com/fr)

## **3. Miscellaneous**


### **3.1 Backslash Escapes**

Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formatting syntax. For example, if you wanted to surround a word with literal asterisks (instead of an HTML `<em>` tag), you can use backslashes before the asterisks.

Markdown provides backslash escapes for the following characters:

1. `\`    backshlass

2. ``` ` ```  backtick

3. `*`   asterisk

4. `_`   underscore

5. `{}`  curly braces

6. `[]`  square brackets

7. `()`  parentheses

8. `#`   hashtag

9. `+`   plus sign

10. `-`   minus sign (hyphen)

11. `.`   dot

12. `!`  exclamation mark


### **3.2 Automatic Links**

If an e-mail adress or a website link is put w/o any markup synthax, Markdown will automatically "translate" it into usable links:

For example, this : ``https://fr.wikipedia.org/wiki/Queen`` will become this : https://fr.wikipedia.org/wiki/Queen, awesome isn't it? 

<br/>  

In fact, Markdown will refer to the adress in HTML code like this :
```HTML 
<a href="https://fr.wikipedia.org/wiki/Queen">https://fr.wikipedia.org/wiki/Queen</a>
```
It's the same procedure with an e-mail address as address@example.com referred like this in Markdown :

```HTML
<a href="&#x6D;&#x61;i&#x6C;&#x74;&#x6F;:&#x61;&#x64;&#x64;&#x72;&#x65;
&#115;&#115;&#64;&#101;&#120;&#x61;&#109;&#x70;&#x6C;e&#x2E;&#99;&#111;
&#109;">&#x61;&#x64;&#x64;&#x72;&#x65;&#115;&#115;&#64;&#101;&#120;&#x61;
&#109;&#x70;&#x6C;e&#x2E;&#99;&#111;&#109;</a>
```

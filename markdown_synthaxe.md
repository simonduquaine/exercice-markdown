# La Synthaxe et l'utilisation du Markdown 

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

### **1.2 Headers**

<<<<<<< HEAD
### **1.3 Blockquotes**
=======
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
>>>>>>> ajouts-jurgen

### **1.4 Lists**

### **1.5 Code Blocks**

### **1.6 Horizontal Rules**


## **2. Span Elements**


### **2.1 Links**
<<<<<<< HEAD
=======
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

>>>>>>> ajouts-jurgen

### **2.2 Emphasis**

### **2.3 Code**

### **2.4 Images**


## **3. Miscellaneous**


### **3.1 Backslash Escapes**

### **3.2 Automatic Links**
<<<<<<< HEAD
=======
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
>>>>>>> ajouts-jurgen

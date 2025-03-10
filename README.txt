On most websites, behind the scenes Apache is running. It serves your webpages.
The default configuration of Apache was to serve <index> file if no file was mentioned. 
So creating an index file is standard practice.

Emmit helps us speed up our code with the help of abbreviations. VScode includes Emmit by default.

Live Server helps to reflect changes in your file on the browser without the need of reloading

It is known that a heading in h1 tag is bigger than a heading in h2 tag.
But this is not true, we can make the heading in h2 even larger than h1 using css.
h1 means that this is the core part of the page 
similarly h2 means it is a subheading and holds less importance.
Structuring your page helps browser understand it better.


HTML is a structure language, gives structure to your page

tags are not case sensitive


boiler plate explained : 
<!DOCTYPE html>
<html lang="en">
<head>

</head>
<body>
    
</body>
</html>

Since HTML is not the only markup language, there are others like xml, xhtml, latex. So we need to tell the browser that what language is our document using. To do this we use "DOCTYPE"

<html lang="en"></html> defines the language we are using

<html> has 2 children <head> and <body> which can further have more children

<body> contains all the visual part of the page 
<head> has only 2 things to display - title and favicon(icon)

<meta> tags are used to give information to the server or any bots that visit the site which don't want to display

https://developers.google.com/search/docs/crawling-indexing/special-tags 
link to know about meta tags


Tags, Elements and Attributes

<h1 title = "Heading one">Heading2</h1>

Here, the complete thing is an element 
h1 is a tag 
and title is the tag's property called attribute
Note : title tag shows when you hover over the heading. title is a global attribute and can be used with any tag


It is good practice to close all elements. If it doesn't support a closing tag then make it self closing
example : <br />

anchor tag is used to open an external link and it has an attribute href

You can use Mozilla Developer Network(mdn) to know more about a tag and it's attributes.

Some attributes are compulsory like href otherwise a tag won't work 

**we can type p>lorem20 and this will tell emmit to generate a paragraph with 20 words 

<pre> tag helps us retain indentation while <p> does not. But <pre> tag's attributes are deprecated and most browsers don't support them.


<!-- dsfasdfas --> 
format for commenting


<b> vs <strong>
<b> is just to make some text bold and draw attention
<strong> is used to strong importance to something, like warnings.
The effect looks the same but it's good to use proper structure. <strong> might give a different effect in certain browsers.

similarly there are <i> and <em> (emphasis) tag.

<i> tag is used for Alternative voice or mood, Taxonomic designations (such as the genus and species "Homo sapiens"),Thoughts (such as "She wondered, What is this writer talking about, anyway?") etc

<em> tag is to put emphasis on the content
A person or software reading the text would pronounce the words in this tag with an emphasis, using verbal stress.

<ul> -> unordered list

ul>li*5 : makes an unordered list with 5 elements


The <small> HTML element represents side-comments and small print, like copyright and legal text. By default, it renders text within it one font-size smaller

<sub> and <sup> Tags
The <sub> HTML element specifies inline text which should be displayed as subscript 
The <sup> HTML element specifies inline text which is to be displayed as superscript    

<del> and <ins>
The <del> HTML element represents a range of text that has been deleted from a document. This can be used when rendering "track changes" or source code diff information, for example. The <ins> element can be used for the opposite purpose: to indicate text that has been added to the document.

The <mark> HTML element represents text which is marked or highlighted for reference or notation purposes.
<mark> indicates a portion of the document's content which is likely to be relevant to the user's current activity. This might be used, for example, to indicate the words that matched a search operation.

We can provide styling in another file using css or we can provide in the same html file using <style> tag inside <head> tag.

Both methods of styling can override each other depending upon where they are declared, the later one overrides the prior one.

Also if we style an individual element it will override the style given in head

blockquote helps browser recognize quotes and it helps in search results

The <address> HTML element indicates that the enclosed HTML provides contact information for a person or people, or for an organization.

The <cite> HTML element is used to mark up the title of a cited creative work. 
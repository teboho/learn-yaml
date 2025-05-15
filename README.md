# YAML => YAML Ain't A Markup Language

Unlike HTML or the gazillon versions of XML, YAML is not a mark-up language, we don't use it to mark up content. 
Markup languages, by definition, attempt to markup content, most of them have special tags with attributes and 
the like to specifically markup content and present it in a certain format that beautifies it or make it look much 
more appealing and less raw than it would look if it was just text in a notepad for example. In a way Markdown also 
does this, because by the time it renders, it (the content) no longer looks the exact same way it was written 
in the text file that was written up to prepare the content. HTML and XML uses these tags and attributes to do 
the marking up for example:

to mark up the text "Let's Learn HTML" as a heading of level one, it would be marked up thus  
```<h1>Let's Learn HTML</h1>```  
, with Markdown to mark "Let's Learn Markdown" up (or down xD) as a heading you would would write the raw text content as  
```# Let's Learn Markdown```  
.

You see, in a way doing mark up or mark down on your content using mark up languages, what you are really doing 
is that you are decorating the content that you are trying to present to your reader.

We say YAML Ain't A Markup Language because while the aim is "still" to present the content as readable and concise, 
we are not necessarily concerned with beauty. We are more concerned with structure, are we goruping relating parts 
of the content correctly in a way that is both intuitive and conscise (structurally) to the reader?  
The interesting and fun part is that the reader can be both the Human and the Computer :).

An example of yaml can look like this
```YAML
programmers:
- Zuck
- Teboho
- Drew
```

You see, we use the structure to help us make the point about the information we are relaying to the reader. This is great!  
Once the intuition kicks in, it becomes as easy to write YAML as it is to read it, because really, at the heart of it, WYSIWYG - What You See Is What You Get.

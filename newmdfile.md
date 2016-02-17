* Markdown original: 2004, considered good but not enough
* Enhanced Versions:
 * Markdown Extra -> PHP Module
  * Multi-Markdown -> Extended markdown syntax adopted by a pop editor, is original markdown + markdown extra + personal enhancements
  * GitHub flavored markdown -> Most popular markdown today
  * Several more...




# =========ORIGINAL MARKDOWN SYNTAX=========
---




#Paragraph Examples

This is my first paragraph example.

This is my second paragraph example.

This example will feature a break
about here but it will show up on the same line.

In this example, I will use a hard break  
to force a break here by using two spaces  
at the end of a line.




Header 1
=======

Header 2
-----------

# Also Header 1

## Also Header 2

### Also Header 3

###### Also Header 6 -> Smallest




#Text Attributes

In this first sentance I will _really_ place *emphasis* on my words in two different ways.

Next, I will write __very strong__, **bold** text, also in two different ways.

This example will contain an _intra_word emphasis. This is a variable name var_example_int but markdown will render emphasis by default

This example will contain an _intra_word emphasis. This is a variable name var\_example\_int but markdown will render emphasis by default until we add the backslashes to escape them. This is the safest. var\_example_int also works but not for all versions.




# Quote Example

>Always remember that you are absolutely unique.  
Just like everyone else.

#### -_Margaret Mead_




# Code Examples


This `rm` command is used to delete in Bash. For example:

    cd ~
    ls -l
    rm myfile.txt
    #this is a comment
    var test = `test`

I used four spaces to start the code block.

If you want help with the `rm` command, use `man rm` to generate the manual page.



#List Examples

### Places to Shop
* Supermarket  
+ Mall  
- Gas  

This is an unordered list. All three symbols can be used.

Don't forget to use a space after the symbol!


### States by Population
1. Ca
8. Tx
0. FL
7. NY

Markdown does not care about the numbers you used. It will not re-order the list but will fix the numbering. This can be problematic, so be cautious.


## Favorite foods with sublists
* Fruit
    * Watermelon
    * Oranges
* Veggies
    * Carrots

Use four spaces if needed. The standard is two spaces. This is a matter of contention.


### Favorite Foods
1. Fruits are really good for you.  
Get at least 1-2 servings per day
1. Veggies are great for vitamins and
minerals.

This item contains a quote
>Some quote here





/// Start of NON-STACKEDIT-FRIENDLY Example
{This section will not work in most text editors. Please consider downloading a desktop version, or using GistHub}

## Horizontal Rulea



Above the line
***
Below

This will not be made a header thanks to that linebreak

---

Luckily underscore character needs to alteration
___  
Like so

}
/// END OF NON-STACKEDIT SECTION





# Links Example

### Unreferenced links

One of the most popular search engines is [Google](http://google.com "Google your Search").

A distant second is Microsoft's [Bing][msb]

### Referenced links

[msb]: http://bing.com "The Bing search engine"
>"Don't forget the spaces!" -_Me_


### Automatic links

<http://www.google.com>

<yourEmail@yourEmailProvider.ext>





# Images Example

> "... images within markdown is not a super-intuitive concept." -_Jason Taylor_


### inline images
This is a line image:
![Demo](http://placehold.it/350x150)


### Referenced Images
Placehold.it is a nice place to get some placeholder graphics
![300x300 demo][Demo300]

[Demo300]: http://placehold.it/300 "300-pixel sqaured placeholder. This is the alt-text"

>"This is how you define the variable. Using the `!` mark as above, you can reference it that way."-_Me_




#Inline HTML Example

Sometimes you need to add some inline HTML.  
Definition lists are not supported by core-markdown syntax.


<dl>
  <dt> Markdown </dt>
  <dd> An awesome plain-text format
</dl>


### Here is the code for a definition list in HTML using 4 spaces

    <dl>
      <dt> Markdown </dt>
      <dd> An awesome plain-text format
    </dl>
	
	
	


# =========ENHANCED MARKDOWN=========
---
	



# Table Example

|	Col Hd 1	|	Col Hd 2	|	Col Hd 3	|
|	----------	|	----------	|	----------	|
|	R	1,	C	1	|	R	1,	C	2	|	R	1,	C	3	|
|	R	2,	C	1	|	R	2,	C	2	|	R	2,	C	3	|
|	R	3,	C	1	|	R	3,	C	2	|	R	3,	C	3	|

This is above the table #1

|	Col Hd 1	|	Col Hd 2	|	Col Hd 3	|
|	----------	|	:----------:	|	----------	|
|	R	1,	C	1	|	R	1,	C	2	|	R	1,	C	3	|
|	R	2,	C	1	|	R	2,	C	2	|	R	2,	C	3	|
|	R	3,	C	1	|	R	3,	C	2	|	R	3,	C	3	|

This is above the table #2

|	Col Hd 1	|	Col Hd 2	|	Col Hd 3	|
|	----------	|	:----------	|	----------	|
|	R	1,	C	1	|	R	1,	C	2	|	R	1,	C	3	|
|	R	2,	C	1	|	R	2,	C	2	|	R	2,	C	3	|
|	R	3,	C	1	|	R	3,	C	2	|	R	3,	C	3	|

This is above the table #3

|	Col Hd 1	|	Col Hd 2	|	Col Hd 3	|
|	----------	|	----------:	|	----------	|
|	R	1,	C	1	|	R	1,	C	2	|	R	1,	C	3	|
|	R	2,	C	1	|	R	2,	C	2	|	R	2,	C	3	|
|	R	3,	C	1	|	R	3,	C	2	|	R	3,	C	3	|

This is above the table #4





#Fenced Code Blocks with optional Syntax for Markdown flavors that support it

This is code, below.

```
#!/user/bin/env ruby
print "Hello Ruby!\n"
print "Goodbye Ruby!\n"
```

This is code, above.

Some flavors allow language-specific syntax specifiers.


```ruby
#!/user/bin/env ruby
print "Hello Ruby!\n"
print "Goodbye Ruby!\n"
```


```java
import java.io.*;
public class Foo(){
	public static void main(String[] args){
		System.out.println("this is a test");
	}
}
```





# Outlining and Brainstorming

## Wordpress Introduction

###Introductions
* Welcome
* About the Series/Course
* Overview or Wordpress and its History
  * Open source nature of wordpress

###Basics
* How it works
  * Blogging platform
  * Website platform
* Installing
  * Self-hosted vs Wordpress.com
* Blogs
* Pages
* Plugins

###Advanced
* SEO
* Themes
* e-commerace

###Conclusion
* Review
* More resources





#Novel Example

##__THE ADVENTURES OF TOM SAWYER__

###By __Mark Twain__  
###(Samuel Langhorne Clemens)

####PREFACE  

Most of the adventures recorded in this book really occurred; one or two
were experiences of my own, the rest those of boys who were schoolmates
of mine. Huck Finn is drawn from life; Tom Sawyer also, but not from an
individual--he is a combination of the characteristics of three boys whom
I knew, and therefore belongs to the composite order of architecture.

The odd superstitions touched upon were all prevalent among children and
slaves in the West at the period of this story--that is to say, thirty or
forty years ago.

Although my book is intended mainly for the entertainment of boys and
girls, I hope it will not be shunned by men and women on that account,
for part of my plan has been to try to pleasantly remind adults of what
they once were themselves, and of how they felt and thought and talked,
and what queer enterprises they sometimes engaged in.

####THE AUTHOR.

####HARTFORD, 1876.


###__CHAPTER I__

>"TOM!"

No answer.

>"TOM!"

No answer.

>"What's gone with that boy,  I wonder? You TOM!"

No answer.

The old lady pulled her spectacles down and looked over them about the
room; then she put them up and looked out under them. She seldom or
never looked _through_ them for so small a thing as a boy; they were
her state pair, the pride of her heart, and were built for "style," not
service--she could have seen through a pair of stove-lids just as well.
She looked perplexed for a moment, and then said, not fiercely, but
still loud enough for the furniture to hear:

>"Well, I lay if I get hold of you I'll--"

She did not finish, for by this time she was bending down and punching
under the bed with the broom, and so she needed breath to punctuate the
punches with. She resurrected nothing but the cat.

>"I never did see the beat of that boy!"






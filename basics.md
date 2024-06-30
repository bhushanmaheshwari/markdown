# Markdown Basics

## 1. Paragraphs and Line Breaks

This is my first paragraph example.

This is my second paragraph examples

This example will feature a break
about here but it will show up on 
the same time

In this example, I will use a hard  
break using two spaces  
and then it will break in lines


## 2. Headers

**use # marks** upto 6

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6


## 3. Text Attributes Example

In this first sentence, I will _really_ place *emphasis* on my words
in two different ways.

Next, I will write __very__, **strong** or bold text, also in two
different ways.

This exmaple will contain _intra_word emphasis. This is variable
name var\_example\_int but Markdown will render emphasis by default.  
Safer way to use *aste*risk for intraword emphasis.


## 4. Quotes

> Always remember that you are absolutely unique. Just like everyone else.
> Just like everyone else.

##### Bhushan Maheshwari


## 5. Source Code Examples

This is `rm` command used to delete files in Bash.  

For example - for any code block, you can also **indent by 4 spaces** as below

    cd ~
    ls - l
    rm myfile.txt
    # also ignores reserve words
    var test = 'test'

This `rm` command has many options, which can be seen using `main rm`


## 6. List Examples

**unordered list**
- Supermarket
- Mall
- Gas Station

**ordered list**
1. California
2. Texas
3. Florida
4. New York

**nested list**
- Fruits
  - Melon
  - Mango
- Veggies
  1. Carrots
  2. Spinach
     This is good for vitamins and minerals


## 7. Horizontal Rules

Paragraph 1 Starts

---

***

___

Paragrah 2 ends


## 8. Referencing Links

One of the most popular search engines is [Google] (http://google.com "Google Search")

A distant second is Microsoft's [Bing][msb].

[msb]:http://bing.com "Bing Search Engine"

**Automatic Links**

<http://google.com>

<bhushan.promo@gmail.com>


## 9. Images

**Inline Imaged**

This is an inline image - web url   
![Demo](http://placehold.it/350x150)

It could be a localfile url image as well


**Referenced Images**

Placehold.it is a nice place to get some placeholder graphics.   
![300x300Demo][Demo300]


[Demo300]:http://placehold.it/300 "300 pixel squared"


if you add text in between, it might not work
[Demo300]:http://placehold.it/300 "300 pixel squared"


## 10. Inline HTML

Sometimes you neeed to add some inline HTML.

<dl>
  <dt>
    Markdown
  </dt>
  <dd>
    An Awesome plain-text format
  </dd>
</dl>

Here is the code I used for above HTML

    <dl>
      <dt>
        Markdown
      </dt>
      <dd>
        An Awesome plain-text format
      </dd>
    </dl>


  





























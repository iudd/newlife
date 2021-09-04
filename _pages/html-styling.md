---
ID: 136
post_title: Html Styling
post_name: html-styling
author: zdlife
post_date: 2018-04-27 08:42:28
layout: page
link: http://iyoud.freetzi.com/html-styling/
published: true
tags: [ ]
categories: [ ]
---
Below is just about every HTML element you might want to use in your blog posts. Check the source code to see the many embedded elements within paragraphs.

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

Lorem ipsum dolor sit amet, [test link][1] adipiscing elit. **This is strong.** Nullam dignissim convallis est. Quisque aliquam. *This is emphasized.* Donec faucibus. Nunc iaculis suscipit dui. 5<sup>3</sup> = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. <cite>The New York Times</cite> (That’s a citation). <span style="text-decoration:underline;">Underline.</span> Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. To copy a file type `COPY <var>filename</var>`.

<del>Dinner’s at 5:00.</del><ins>Let’s make that 7.</ins>

This <span style="text-decoration:line-through;">text</span> has been struck.

* * *

## List Types

### Definition List

Definition List Title
:   This is a definition list division.

Definition
:   An exact statement or description of the nature, scope, or meaning of something: *our definition of what constitutes poetry.*

* * *

### Ordered List

1.  [List Item 1][2]
2.  [List Item 2][2] 
    1.  [Nested list item A][2]
    2.  [Nested list item B][2]
3.  [List Item 3][2]

* * *

### Unordered List

*   [List Item 1][2]
*   [List Item 2][2] 
    *   [Nested list item A][2]
    *   [Nested list item B][2]
*   [List Item 3][2]

* * *

## Table

<table>
  <tbody>
    <tr>
      <th>
        Table Header 1
      </th>
      
      <th>
        Table Header 2
      </th>
      
      <th>
        Table Header 3
      </th>
    </tr>
    
    <tr>
      <td>
        Division 1
      </td>
      
      <td>
        Division 2
      </td>
      
      <td>
        Division 3
      </td>
    </tr>
    
    <tr class="even">
      <td>
        Division 1
      </td>
      
      <td>
        Division 2
      </td>
      
      <td>
        Division 3
      </td>
    </tr>
    
    <tr>
      <td>
        Division 1
      </td>
      
      <td>
        Division 2
      </td>
      
      <td>
        Division 3
      </td>
    </tr>
  </tbody>
</table>

## Preformatted Text

Typographically, preformatted text is not the same thing as code. Sometimes, a faithful execution of the text requires preformatted text that may not have anything to do with code. For example:

<pre>“Beware the Jabberwock, my son!
			The jaws that bite, the claws that catch!
			Beware the Jubjub bird, and shun
			The frumious Bandersnatch!”</pre>

### Code

Code can be presented inline, like `<?php bloginfo('stylesheet_url'); ?>`, or within a `<pre>` block.

    #container { float: left; margin: 0 -240px 0 0; width: 100%; }

## Blockquotes

Let’s keep it simple.

> Good afternoon, gentlemen. I am a HAL 9000 computer. I became operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992. My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to hear it I can sing it for you. <cite>— <a href="http://en.wikipedia.org/wiki/HAL_9000">HAL 9000</a></cite>

 *[HTML]: HyperText Markup Language
 *[CSS]: Cascading Style Sheets

 [1]: # "test link"
 [2]: # "list"
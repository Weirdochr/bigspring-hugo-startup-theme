---
title: Machine Learning in Display Front-of-screen (FOS) Inspection
date: '2020-04-18T10:07:21.000+06:00'
image: images/blog/post-1.jpg
type: featured
description: This is meta description

---
## Machine Learning in Display Front-of-screen (FOS) Inspection

Display front-of-screen is a very key component of devices like iPhone, iPad, etc, as users spend an inordinate amount of time staring at and interact with every day. The quality of display front-of-screen will dramatically affect users’ experience, which we value the most at Apple. For each new product release, Apple will innovate its display to deliver an optimal viewing experience. In order to deliver the high-quality display front-of-screen, it involves numerous effects from initial design to production and quality control process.

### ![Display front-of-screen inspection from module vendor to assembly line](/images/2020-07-15-4-52-57-2.png "Display front-of-screen inspection from module vendor to assembly line")

_Display front-of-screen inspection from module vendor to assembly line_

### Problem

Apple has long used computer vision to inspect display front-of-screen and the inspection at the product assembly line serves as the gatekeeper of quality control. In the current inspection workflow, firstly the test station returns ‘Pass’ or ‘Fail’ for each device, followed by the inspectors to double-check for both ‘Pass’ and ‘Fail’ results. However, there’re two main constraints in this workflow: for test station, traditionally involved hard-coded and pre-defined rules cannot capture unanticipated defects, like arbitrary and vague defects, making it less sensitive to defect pattern changes; for inspectors, it is easy to make a biased and wrong judgment due to insufficient working experiences and eye fatigue.

![](/images/fosworkflow.png)

_Current inspection workflow_

To tackle above challenges, AI/ML China Team partnered with Display Hardware Testing Engineering Team (HWTE), and successfully delivered machine learning solutions to transform the subjective test to a smarter and more autonomous way.

### Heading 3

<br>

#### Heading 4

<br>

##### Heading 5

<br>

###### Heading 6

<hr>

##### Emphasis

Emphasis, aka italics, with _asterisks_ or _underscores_.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

<hr>

##### Link

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link](https://www.themefisher.com)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions](https://gethugothemes.com)

Or leave it empty and use the [link text itself](https://www.getjekyllthemes.com).

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or [http://www.example.com](http://www.example.com) and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

<hr>

##### Paragraph

Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam nihil enim maxime corporis cumque totam aliquid nam sint inventore optio modi neque laborum officiis necessitatibus, facilis placeat pariatur! Voluptatem, sed harum pariatur adipisci voluptates voluptatum cumque, porro sint minima similique magni perferendis fuga! Optio vel ipsum excepturi tempore reiciendis id quidem? Vel in, doloribus debitis nesciunt fugit sequi magnam accusantium modi neque quis, vitae velit, pariatur harum autem a! Velit impedit atque maiores animi possimus asperiores natus repellendus excepturi sint architecto eligendi non, omnis nihil. Facilis, doloremque illum. Fugit optio laborum minus debitis natus illo perspiciatis corporis voluptatum rerum laboriosam.

<hr>

##### Ordered List

1. List item
2. List item
3. List item
4. List item
5. List item

<hr>

##### Unordered List

* List item
* List item
* List item
* List item
* List item

<hr>

##### Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

<hr>

##### Blockquote

> This is a blockquote example.

<hr>

##### Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
<dt>Definition list</dt>
<dd>Is something people use sometimes.</dd>

<dt>Markdown in HTML</dt>
<dd>Does _not_ work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

<hr>

##### Tables

Colons can be used to align columns.

| Tables | Are | Cool |
| --- | :---: | ---: |
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less | Pretty |
| --- | --- | --- |
| Still | renders | nicely |
| 1 | 2 | 3 |

<hr>

##### Image

![image](../../images/blog/post-6.jpg)

<hr>

##### Youtube video

{{< youtube C0DPdy98e4c >}}
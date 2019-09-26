---
title: "CS164: Computer Networks, Fall 2019"
layout: archive
author_profile: true
permalink: /teaching/
---

#### Instruction Time: 
Wednesdays and Fridays, 2:00 pm - 3:20 pm. Room: WCH 143
#### Instructor: 
K. K. Ramakrishnan,  Room: Winston Chung Hall 332.
#### Instructor Office Hours: 
Wednesdays 4:00 pm - 5:00 pm.
#### Lab: 
Monday 11:00 am - 1:50 pm, Friday 11:00 pm -1:50 pm;  Winston Chung Hall 132
#### Teaching Assistants: 
Shixiong Qi (sqi009@ucr.edu) and Liang Zhou (lzhou008@ucr.edu)
#### TA Office Hours:
For Shixiong: TBD
For Liang: TBD


### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Class Schedule

| Class | Data   | Topics                          | Materials  | Notes
| ----- | ------ | ------------------------------- | ---------- |
| 1     | 27-Sep | Overview of Computer Networks   | Chapter 1  | Overview, Application Layer, HTTP
| 2     | 2-Oct  | Overview of Computer Networks   | Chapter 1  | Overview, Application Layer, HTTP
| 3     | 4-Oct  | Application Layer               | Chapter 2  | HTTP, FTP, SMTP
| 4     | 9-Oct  | Application Layer               | Chapter 2  | DNS,P2P
| 5     | 11-Oct | Application Layer               | Chapter 2  | Socket Programming
| 6     | 16-Oct | Transport Layer                 | Chapter 3  | Intro to Transport, UDP
| 7     | 18-Oct | Transport Layer                 | Chapter 3  | Principles of Reliable Transport
| 8     | 23-Oct | Transport Layer                 | Chapter 3  | TCP Fundamentals
| 9     | 25-Oct | 1st Mid Term Exam               | Exam 1     | Covers Chapter 1, 2 and 3
| 10    | 30-Oct | Transport Layer                 | Chapter 3  | TCP Congestion Control, Fairness
| 11    | 1-Nov  | Network Layer                   | Chapter 4  | Routers: Forwarding, Addressing (IPv4, IPv6), Lookup Algorithms
| 12    | 6-Nov  | Network Layer                   | Chapter 4  | Routing Algorithms: Link State Routing and OSPF
| 13    | 8-Nov  | Network Layer                   | Chapter 4  | Distance Vector Routing and BGP
| 14    | 13-Nov | Network Layer                   | Chapter 4  | IP Multicast
| 15    | 15-Nov | Datalink Layer                  | Chapter 5  | Intro' and Error-Detection and Correction
| 16    | 20-Nov | Datalink Layer                  | Chapter 5  | Multiple Access Links and Protocols
| 17    | 22-Nov | 2nd Mid Term Exam               | Exam 2     | Material covered between Exam 1 and Nov. 20, 2019
| 18    | 29-Nov | Datalink Layer                  | Chapter 5  | Switched LANs and Data Center Networks
| 19    | 4-Dec  | Wireless Networks               | Chapter 6  | Wireless LAN Architecture and MAC (based on previous editions,I may not be able to cover Chapter 6)
| 20    | 6-Dec  | Cellular Networks and Mobility  | Chapter 6  | Cellular Networks and Mobility Management (based on previous editions,I may not be able to cover Chapter 6)
| 21    | 10-Dec | Final Exam                      | Final Exam | Final Exam (11:30 am - 2:30 pm)


## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.

{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
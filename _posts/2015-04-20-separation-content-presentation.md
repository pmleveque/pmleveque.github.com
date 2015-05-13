---
layout: post
title:  "Is it relevant to split raw content and its presentation?"
categories:
---

When I started learning how to make websites, a new norm called xhtml had just been released, and it was supposed to be the successor of html 4. I was a strong supporter[^1] of this new norm because I was excited by the prospect of building clean websites[^2], compliant with xml[^3]. Ten years later, xhtml has been abandoned and there is only html5. What happened with xhtml? Why was I wrong?

[^1]: I had this kind of opinions: [Crime 4: Using `<b>` and `<i>` for Bolding and Italicizing](http://line25.com/articles/10-html-tag-crimes-you-really-shouldnt-commit)

[^2]: on the separation from content and presentation, see [CSS on wikipedia](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#Advantages)

[^3]: "To return HTML to its role as a semantic language, the W3C has developed style languages such as CSS and XSL to shoulder the burden of presentation." [en.wikipedia.org/wiki/XHTML](http://en.wikipedia.org/wiki/XHTML)

Many of us developers believed we could rebuild the Word Wide Web on new foundations. Originally, html was designed as a semantic language, but in practice, it has been used to build complex layouts. The Word Wide Web was designed for humans; what mattered was what appeared, what was displayed in the browser.

With xhtml, the main objective was adapting the web for robots. Pages were to be raw knowledge, organized in a mathematical way. This was a delight for algorithms.

But, why was it important to satisfy robots?[^4]

[^4]: Many people still believe that Artificial Intelligence is something of the future and that robots pertain only to science fiction. Those working in the high-tech sector know that this is already reality. [The core business of Google and Facebook is Artificial Intelligence](http://www.mercurynews.com/business/ci_25627092/google-facebook-and-other-tech-companies-race-develop). No doubt it is widespread.

One reason was Search Engine Optimization (SEO): early search algorithms did not care about presentation. What mattered for them was the beauty of the source code of the web page. 
Another reason was the possibility to broadcast the information on all kinds of devices. Before the advent of smartphones, the layout of web pages was too heavy. With xhtml you could get only the text. In theory, mobile-specific websites were not necessary, because a true xhtml website would have been ready for any use.

One more argument in favor of xhtml: blind people could explore the contents of any compliant website, through specific softwares, because their visual presentation was accessory.
At the end, xhtml was a remedy to obsoletes websites, since the layout and styles were supposed to be distinct from the data. Changing the stylesheet was the only necessary thing.

So xhtml promised to satisfy everyone: in one file, you put the raw contents, and in another file, the presentation of it. Your browser automatically applied the layout to the raw content and displayed the website, and so the basic user was not aware of any difference between the old html site and the new xhtml one. And yet, it was a big progress for robots and their algorithms.[^5]

[^5]: Am I wrong? According to [webdevout.net/articles/beware-of-xhtml](http://www.webdevout.net/articles/beware-of-xhtml), “XHTML does not promote separation of content and presentation any more than HTML does. XHTML has all of the same elements and attributes (including presentational ones) that HTML has, and it doesn't offer any additional CSS features. Semantic markup and separation of content and presentation is absolutely possible in HTML, and with equal ease. In terms of semantics, HTML 4.01 and XHTML 1.0 are exactly the same.” This seems to contradict what I write in this article. In fact HTML 4.01 makes it possible to do all that xhtml promotes. In theory, yes, html 4 and xhtml are not very different. But in practice, the vast majority of websites designed with html 4 had no separation of presentation and contents (even those using CSS). Furthermore, xhtml 1.0 was meant to be a transition towards a stricter language. To be exact, when I refer to html 4 in this article, I have in mind what it was actually in the hands of webs developers, and with xhtml, I designate the intention of those who imagined this new specification. This is schematic, but is makes it easier to understand the point.

This was our hope. And almost none of it prove to be true. It was not only idealistic; it revealed a misconception of the nature of information.

What happened?

First, many web developers started cheating. Their websites looked different for robots and for humans.[^5-1]  In this case, the blind were not taken into account and neither were other devices. The raw xhtml page was pretty for robots, and the displayed page was pretty for the rest of us.

[^5-1]: Black hat SEO http://www.webopedia.com/TERM/B/Black_Hat_SEO.html 

The googlebots had to adapt. Instead of searching the theoretical website with its beautifully organized syntax, they had to search the page as it was shown to the user, because Google’s customers are not robots, but humans.
In that case, xhtml proved irrelevant.
When the first iPhone was launched, one of its best features was its ability to see the whole website, as displayed on a desktop monitor. Obviously, the customer isn’t only interested in raw contents, but the native experience matters to him. Yet another point again pure xhtml.

To sum it up: if robots are interested in the layout of your website, and if smartphones users want a native experience, why should you distinguish the content and its layout? You don’t have to, this is why xhtml was abandoned and html5 eventually released.[^6]

[^6]: However, html5 didn’t abandon the separation between content and layout. It is a still good practice to use html and css in different files since this makes it easier to design. As software engineers, we take pride in beautifully designed websites, and beautiful means being respectful of the norms.
In theory, html5 inherited a lot from xhtml. In practice, the philosophy is radically different. html5 pages are full of hacks, and in a way, they are not different from original html.

What was wrong with xhtml?
HTML inventor and W3C chair Tim Berners-Lee sees the failure of xhtml as transitional[^7]. He still believes the future of html is xhtml, so that all can “enjoy the fruits of well-formed systems”, but it has to be done step by step. That will probably happen eventually, however it does not address the real problem. I don’t believe in a “transition to [a] well-formed world”, on a contrary, I believe we should oppose it[^8]. Let’s try to get a philosophical insight on it.


[^7]: Quoted on [wikipedia](http://en.wikipedia.org/wiki/XHTML#Criticism) : "Tim Berners-Lee (2006-10-27). "Reinventing HTML". Retrieved 2007-06-16. Some things are clearer with hindsight of several years. It is necessary to evolve HTML incrementally. The attempt to get the world to switch to XML, including quotes around attribute values and slashes in empty tags and namespaces all at once didn't work. The large HTML-generating public did not move, largely because the browsers didn't complain. Some large communities did shift and are enjoying the fruits of well-formed systems, but not all. It is important to maintain HTML incrementally, as well as continuing a transition to [a] well-formed world, and developing more power in that world." "The plan is to charter a completely new HTML group. Unlike the previous one, this one will be chartered to do incremental improvements to HTML, as also in parallel xHTML. It will have a different chair and staff contact. It will work on HTML and xHTML together. We have strong support for this group, from many people we have talked to, including browser makers."

[^8]: I am not an opponent of norms and specifications. I think the _WWW_ is not the place where raw contents should be published. Nevertheless I strongly support better javascript and xml APIs, and a better diffusion of free high-quality contents through it.

This step in the history of the Word Wide Web is a practical refutation of a certain idealism. Many engineers today, if not all of them, believe that the idea is more important than the matter. In other words, only structured information has value. Raw data — sounds, images — have to be processed, and useful information has to be extracted from it, or else it is worth nothing.
A common belief is that we are not very different from machines: we think as machines and our body and senses make it possible to extract information from the word around us. In that case, the appearance of things is not important, but only the raw information that we can get from them.

I used to think this way. I wanted to get rid of paper, of handwriting, of any useless wrapping. I wanted to store everything on my computer as unformatted text data, indexed with keywords, organized in a logical structure (folders), so that it could be more easily processed and searched. I wanted my computer to store any piece of knowledge the way my brain does: in a logical way.

Until I understood — first — that my brain had nothing to do with logic and mathematical organization, and — second — that this was its strength.

The way I intended to structure my personal data was not relevant, because it implied discarding what is most important: the context, the form, the shape, the way it came to me. Data is part of my history, it is associated with happy events, difficult experiences, hope, stress, or loved ones. There lies its value.
The same occurs with websites: most of the time, the data we get from them is secondary. The experience it provides is often more important. And this characteristic of humanity is not a weakness!

I have learned from the failure of xhtml and the failure of my personal data organization. A powerful artificial intelligence algorithm browse the web the way we do: looking at pages – that is: both contents and presentation, without separation. It abstracts contents from it, and this process provides more information than just browsing the well-formated html source of the page.

Separating raw contents from its presentation is part of the process of abstraction: it is a necessary step for every kind of intelligence. However, this separation is not inherent of the nature of things. That is to say: it isn't either in the nature of the Word Wide Web.

One lesson I learned: we software engineers should focus on making products and norms that will benefit immediately our fellow humans, and not building a world for robots. Knowledge is primarily a human thing, not a mathematical structure. Algorithms have to adapt to what knowledge really is, rather than make people stick to a theoretical representation of it.

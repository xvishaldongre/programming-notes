# Programming Notes By billryan

[![Build Status](https://travis-ci.org/billryan/programming-notes.svg?branch=master)](https://travis-ci.org/billryan/programming-notes)

Between the fingers, I have been in contact with programming for more than five years. From the first time I was in contact with the C language to the current knowledge of computer programming, the twists and turns are hard to come by. This online note records my point in the process of learning computer programming. Bit by bit.

# About - About this document

- The orignal online hosting repository for this note is https://github.com/billryan/programming-notes You can view the updates in the github star project.
- The online reading URL is http://prog-notes.yuanbin.me. The online reading page is generated by the gitbook backend. After being pushed to github, it will trigger the compilation of gitbook and travis-ci. The corresponding compiled output download link provides Gitbook official website and Seven cattle download methods, seven cattle link Chinese display is better.
    1. Read on the [website](http://prog-notes.yuanbin.me).
    2. EPUB. [Gitbook] (https://www.gitbook.com/download/epub/book/yuanbin/programming-notes), [Seven Bulls] (http://docs4bill.qiniudn.com/doc/programming_notes_billryan. Epub) - Recommended for iPhone/iPad/MAC. Best for offline viewing, very good results.
    3. Offline html. [Seven cattle] (http://docs4bill.qiniudn.com/doc/programming_notes_billryan_html.tar.gz) - After decompression, the content of the entire website is used for local viewing. Currently, the content is updated frequently, not recommended. download.
    4. PDF. [Gitbook](https://www.gitbook.com/download/pdf/book/yuanbin/programming-notes), [Seven Bulls - Printable Version] (http://docs4bill.qiniudn.com/ Doc/programming_notes_billryan_print.pdf) - Recommended for Desktop. Recommended download version of the seven cattle.
    5. MOBI. [Gitbook] (https://www.gitbook.com/download/mobi/book/yuanbin/programming-notes), [Seven Bulls] (http://docs4bill.qiniudn.com/doc/programming_notes_billryan. Mobi) - Recommended for Kindle. Not tested, it doesn't feel like reading this kind of book on Kindle, even though Kindle's screen is good for eyes...
- The full text is divided into three parts.
    1. The first part is Part I Introduction to Programming, which is a relatively macro introduction to computer programming. It was formerly known as "C/C++ FAQ" released in 2007 (http://www.vcgood.com/BBS/ Forum_posts.asp?TID=1559), I have done a lot of integration on this basis in order to adapt to the booming computer wave.
    2. The second part is an introduction to some methodologies.
    3. Summary of related programming materials.
- Widely advertised: the companion book of this book - [data structure and algorithm / leetcode / lintcode solution] (http://algorithm.yuanbin.me/) is also in the hot update ~

The first part analyzes some of the ideas behind computer programming, and at the same time provides a lot of methodological level skills - the next is also. The purpose is to provide a certain idea for everyone to grasp the programming from the whole, not to be trapped in detail. This book is a prose, and it doesn't disperse. It's programming as a god, and it's a chapter. It's also a popular science article. It's not difficult to understand, even easy and humorous, but don't want it. The expectations of this book are too high, Part I is to understand computer programming from the perspective of a beginner / non-CS professional, the skill is naturally better than the big gods.

## Why do you want to organize and publish this programming note?

It’s better to be happy than to be happy, and you can use Google’s powerful web search function to search for the document after you publish it. Why not?

Just as Xu Sanduo chose to build roads in five classes, we also chose to offer such a booklet with the same conviction. Although our level is limited, I am very willing to share with you the bits and pieces gained on the road of growth. ...

About 2009, when I was a freshman, I didn’t know much about computers. The long-time "computer culture" and C language didn't understand how programming was doing. I just thought that programming was A very magical thing, it is like magic, but in the fog, the flower is separated by a layer, and I have never been able to experience it for myself. At that time, I hope that there will be a Zhuge who can help me to help me, even if it is not Wolong, the phoenix will do it! I think there must be such a small group of people holding this idea now. I just want to say to you, "It should wake up! It is not a Libo dream board now!" ** At any critical moment, the only person who can help you is you. Self, even if you can find someone who is willing to help you, then you have to worry about finding it? **

As a former novice, I know that the transition from a novice to an old bird needs to open the dark clouds of the sky and climb over the mountains... As you can see, the bookstores and the Internet are filled with countless programming materials, and at the same time, you can be sure. Yes, the textbooks that have been available so far are impossible to read. In these books, there are a large number of garbage books, a large number of mediocre works, and a small number of fine works, and even this small number of fine products, it is impossible to see the whole. Since there are so many books, why should I take the time to sort out one? In the words of the blue creator of the blueprint of the book, he can also draw a few more renderings to earn money.

This is the case. There are many books on the market, but few of them are for beginners. Such books are so few that it is very difficult to buy or read them. They are telling you everything at once, as if you can suddenly change from a rookie to a master in a thousandth of a second, or you think that something you should have known for a long time, take you as a master, and lead you to have a naked body. Naked is abandoned in the wilderness of the wild beast. You haven't put on your clothes and walked out of the tent. Even the knives haven't touched them. They try to tell you how many prey can be captured on the prairie and their location. Tell you hundreds of weapons and poison cheats and tell you two hundred. The above traps are placed in the essentials. You haven't practiced the slightest, and you haven't even killed a chicken that has just come out of the shell. They want you to hunt dozens of hungry lions alone. This seemingly ridiculous situation has continued from the past to today and still exists today. This is not to say that those who write textbooks are fools, and the readers they target are professional programmers. Professional programmers are like hunters. They change language like hunters change weapons. No matter which weapon they use, the basic principle of hunting has not changed. The only change is the use of weapons. For a mature hunter, it is not necessary to emphasize the basic principles, so the textbook editors will avoid mentioning some things that people on earth know.

** A mature hunter, his knowledge of hunting is seamless, the choice of weapons, the habits of the beast, the placement of traps, how to do it and why it is done, no part can be independent. ** Part of the teaching of others is extremely difficult, and teaching can only be mixed together. The situation of programming is similar. Its knowledge system is a complete system. When it comes to one problem, it will always involve another. However, the problems that beginners usually encounter are too simple, so that they do not feel the existence of a complete knowledge system. It is only natural to learn in the fog.

So how do you write a textbook for novices? Personally think that in addition to introducing some necessary basic and core knowledge, what is more important is the logic behind the knowledge. It is often difficult for an author with poor skill to dissect it as a singer. At the same time, the process of thinking can only be understood and can not be said, and few people can very well notice the preciousness of the thinking process. These two reasons together lead to the difficulty of copying good textbooks.

### Readers

After reading the above paragraphs, you should be able to guess the service object of this book. That's right, it's for those who have no programming experience but are interested in computers, even those who don't have access to computers. The purpose of this note is also here - ** to introduce some of the background knowledge and beneficial methods necessary for programming, so as to better open the magic door of computer programming. ** If you think you have some programming experience, then you can share this experience of getting started with programming with everyone, perfecting this book or mentioning issues are excellent :)

## Conventions, typesetting and others

The language and syntax used in this book are not exactly the same as formal books. The Chinese and English are mixed throughout the text. Some examples are just for the convenience of explaining the problem, the rigor may not be enough, and occasionally it will be smart or use programming. Commonly used symbols, such as with && for and , || for or, more things are waiting for you to dig. In this revision, I tried to separate Chinese and English. Unnecessary Chinese and English mixing is actually not very friendly to readers.

**The book is not as good as the book **. This note is just a collection of various materials and then combined with my programming experience for a big integration, but the level is limited, can not guarantee that everything is correct and reasonable, The letter between the female and the nonsense is only one step away. Some comments I try to maintain a neutral attitude. The places quoted in this article will try to indicate the source for further reference, and I hope that everyone will read with suspicion.

### Acknowledgement

<dl>
  <dt>Blue Auris</dt>
  <dd>Chinese nickname: Azure right ear, the first part of the raw material creator of this note, the C/C++ FAQ mentioned in the preface is from his hand, and he agrees to re-release it under the public creation license agreement, I just did it. A lot of organization and integration. It can be said that without his C/C++ FAQ, there is no such compilation. I would like to pay a high tribute here! </dd>

  <dt>Everyone</dt>
  <dd>The ultimate perfection of the book, without the hard work and sweat of everyone, there is no such quality note. </dd>
</dl>

### License (license)

![pic](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

Unless otherwise stated, this work is licensed under [Creative Commons Attribution-Share Alike 4.0 International License Agreement] (http://creativecommons.org/licenses/by-sa/4.0/), **Welcome to fork and spread this document , but please note that the above license agreement is followed. **

## Contribution - How to contribute this document

If you find any improvements in this document, please feel free to submit your improvements in the following formats.

1. Become a contributor to this project, send an email and tell me your github account name, I will add your github account to Collaborators after receiving the email.
2. Submit the Pull Request, the github repo of this fork, and send me PR.
3. Submit the issue at the github repo in this document, indicating the problem.
4. Add a comment in the disqus comment box under the website http://prog-notes.yuanbin.me corresponding page, pointing out some typo or areas that can be improved.

### Document Format & Editing Tools - GFM && kramdown Markdown

Written using markdown, using only the markdown syntax supported by gitbook. The underlying markdown renderer of gitbook is changed kramdown, and GFM support is added. The extended markdown syntax supported is very much. For details, see [GitbookIO/kramed] (https://github.com/GitbookIO/kramed)

The recommended markdown editor is gitbook's own [GitbookIO/editor] (https://github.com/GitbookIO/editor), which supports Windows/Linux/MAC three platforms, the industry conscience! However, the actual memory usage may be too high under Arch Linux... The performance is still good under OS X. The editing interface is as shown below. The left side is the chapter preview, the middle is the markdown edit box, and the right side is the real-time rendering. Page, you can choose to use full screen mode.

![Gitbook Editor](./images/gitbook_editor.png)

Using other things like Mou/Vim/Emacs/Sublime Text is also good, but it's a bit of a hassle when adding a Chapter/Section. Well, you can also create a new section and edit it with another editor.

Check out [Gitbook Documentation] (http://help.gitbook.com/) for tips on Gitbook to help you understand how the text and chapters on the http://algorithm.yuanbin.me page are edited and Rendered.

### Chapter name and number

The names of the chapters and other files are all in English. The sub-chapters can be up to three levels. The chapter numbers need not be worried. This kind of trivial matter should be handed over to Gitbook. If you have to manually adjust it, modify the `SUMMARY.md` file and pay attention to the indentation. Relationships, Gitbook expects this to automatically number the chapters.

For example, I want to add "Dynamic Planning" and its sub-chapters now. First find "Add Chapter" in the menu bar "Book" on the top of Gitbook, and fill in "Dynamic Programming". Ok, you can see the newly generated "10. Dynamic Programming" in the left section of the Gitbook. Left click, Gitbook will generate the "dynamic_programming" directory and the description file "dynamic_programming/README.md" in this chapter. . If you want to add a sub-section under "10. Dynamic Programming", right-click on it, "Add Section". Same as above, the sub-section file name still uses the English name. The title displayed on the web page can be changed by name and then added to Chinese.

Well, the above steps can be done directly by creating a new folder and manipulating the `SUMMARY.md` file.

### Mathematical formula

In fact, there is no need to write mathematical formulas in the code, but occasionally the analysis algorithm may be used. LaTeX has been used to know how elegant the math formula she generated is, so that it is a bit uncomfortable to use her to write mathematical formulas...

LaTeX is recommended for more complex mathematical formulas in this document, because it is hosted on gitbook, so it uses a lightweight katex plugin, without the heavyweight MathJax. The inline and interline formulas are both $, the difference is that the interline formula is written to the beginning of the next line, and the inline formula cannot be written at the beginning of the line (nonsense...). Katex is very fragile and does not support some advanced LaTeX syntax, otherwise it will not compile output to the website and pdf, try to use simple LaTeX syntax or not.

### Text writing style

1. Chinese and English mixed throughout the text, elegant and beautiful, as much as possible before and after the English words with spaces, this enabled input method between Chinese and English to add space function just fine.
2. The function name or short code of the code is recommended to use \`code\`
3. Use blank lines for segmentation, um, markdown universal

When working with github, it is good to give a understandable commit when adding/modifying content. For the time being, I thought so much. In fact, I didn’t pay much attention to it. I felt like I’m looking at it clearly. Others think of it. :-)

### Attachments and image references

Pictures are stored in the `images` directory, and other attachments are stored in the `docs` directory. Quoted image links can generally be declared via `![Caption](../images/xxx.png)`.

The size of the image is too large for the page to load. It is recommended to compress it before putting it in. If it is a png image, consider using [TinyPNG – Compress PNG images while preserving transparency] (https://tinypng.com/)

Having said that, it seems like someone really works together... =_= #sigh

## To-Do
[] - Translate other parts
[] - something.. 

## I am not responsible for this 
## I did translation only.

# What's `jekyll-book-theme`?

It's another Jekyll static site generator theme for classic books
(e.g. Strange Case of Dr. Jekyll and Mr Hyde, A Tale of Two Cities, The Trial, etc.)
that is, a ready-to-fork template pack.

See a live demo @ [`drjekyllthemes.github.io/jekyll-book-theme` »](http://drjekyllthemes.github.io/jekyll-book-theme/)

For example:

```
├── _config.yml                               # book configuration
├── _chapters                                 # sample chapters
|   ├── 01.md
|   ├── 02.md
|   ├── ...
|   └── 10.md
├── _layouts                           
|   └── default.html                   # master layout template
├── css                               
|   ├── _settings.scss                 # style settings (e.g. variables)
|   └── style.scss                     # master style page
└── index.html                         # all-in-one page book template
```

will result in an all-in-one book page:

```
└── _site                                # output build folder; site gets generated here
    ├── css
    |   └── style.css                    # styles for pages (copied 1:1 as is)
    └── index.html                       # all-in-one book page
```


## How-to Build Your Own Book

### Step 1: Add your chapters to the `_chapters/` folder

Replace all text files in the `_chapters` folder with your own.


### Step 2: Add the book title and author in the `_config.yml` file

Next change the book title and author in the `_config.yml` file:

~~~
title:  Strange Case of Dr. Jekyll and Mr. Hyde
author:
  name: Robert Louis Stevenson
~~~

with your own book title and author name. That's it. Happy reading.



## Example Classic

### Strange Case of Dr. Jekyll and Mr. Hyde

by Robert Louis Stevenson

> Mr. Utterson the lawyer was a man of a rugged countenance, that was
> never lighted by a smile; cold, scanty and embarrassed in
> discourse; backward in sentiment; lean, long, dusty, dreary, and
> yet somehow lovable.

- [Story of the Door](#) - [(Source)](_chapters/01.md)
- [Search for Mr. Hyde](#) - [(Source)](_chapters/02.md)
- [Dr. Jekyll was Quite at Ease](#) - [(Source)](_chapters/03.md)
- [The Carew Murder Case](#) - [(Source)](_chapters/04.md)
- [Incident of the Letter](#) - [(Source)](_chapters/05.md)
- [Remarkable Incident of Dr. Lanyon](#) - [(Source)](_chapters/06.md)
- [Incident at the Window](#) - [(Source)](_chapters/07.md)
- [The Last Night](#) - [(Source)](_chapters/08.md) 
- [Dr. Lanyon's Narrative](#) - [(Source)](_chapters/09.md)
- [Henry Jekyll's Full Statement of the Case](#) - [(Source)](_chapters/10.md)



### More Free World Classics in Plain Text (.txt)

- [worldclassics @ GitHub](https://github.com/worldclassics) - more ready-to-use free world (literature) classics e.g. The Trial by Franz Kafka, etc.
- [Project Gutenberg](https://www.gutenberg.org) - the world's biggest free classics book library in plain text; more than 40,000+ books collected since 1971 



## Meta

**License**

The theme is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

**Questions? Comments?**

Post them to the [jekyll talk forum](https://talk.jekyllrb.com). Thanks!


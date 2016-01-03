---
layout: post
title: A Template Post
description: A basic template post. # A description is optional.
categories: jekyll blogging how-to # Categories are optional.
# Categories are, sadly, case-sensitive, so you should get in the habit of only using lowercase tags.
---
This is a basic template post, as well as a markdown how-to.

To create a post, create a file in the ```_posts``` directory in your GitHub Pages repository (named ```[your username].github.io```). The name of the post should be ```2016-MM-DD-post-title.md```, where MM is the month, and DD is the day, e.g. a post on January 14th (our first day of class) with the title "Our First Day!", would read ```2016-01-14-our-first-day.md```.

Each post gets "front matter," or the metadata you see at the top of the post server-side. At minimum, you must specify the title. It's a good idea to specify that it's a post. Some of our Jekyll templates include descriptions, others include categories. You can use them or not, as you wish, and as your chosen template demands.

After the front matter, simply write your content in markdown. Save the file, commit the change in GitHub Desktop, and sync the repository. And presto! Your new post is live on GitHub pages.

#### Markdown Basics

Markdown is dead simple, even if it's not quite WYSIWYG. It's plaintext, and most of its formatting is specified by including a few special characters. **\*\*Bold\*\*** and *\*italic\** get one and two asterisks, respectively. Code is enclosed by three back tick marks: \`\`\````code```\`\`\`. (If you'd like your code to include syntax highlighting, you should instead enclose it in slightly fancier tags, like so:

```javascript
var MyObject = function (value) {
  this.value = value;
};

MyObject.prototype = {

  myFunction: function (parameter) {
    this.value = parameter.doStuff();
  }

};
```

Headers are specified by some number of hashes—\#—big headers get one, smaller headers get two, and so on down to five headers.

The other most common thing you will do is make links. In theory, links simply written out, including the http part, should be live once parsed, (e.g. http://eng7006.github.io/). But in most cases, especially when writing pingbacks, you'll want to explicitly link text. The readable text goes in square brackets—[]—and the place to link to goes in regular parentheses—(). Like so: [our ENG 7006 homepage](http://eng7006.github.io/).

> Block quotes are introduced by a little right-pointing arrow thingie (a right angle bracket, to be precise).

Bullet points are specified by asterisks at the beginning of lines (with spaces after them):

* like
* so
* many
* bullet
* points

Use Atom's syntax highlighting to help guide you. For more information on markdown, go to [GitHub's markdown basics](https://help.github.com/articles/markdown-basics/).

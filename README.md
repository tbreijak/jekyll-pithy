Pithy is one of three Jekyll templates that have been customized for our use in ENG 7006.

### Getting Started Blogging with Jekyll
You'll almost certainly only need to interact with this repository exactly once ever, at the beginning of the semester, with Scott present. But, here are some instructions on how to get started blogging with Jekyll.

[View a live demo of Pithy](http://kredati.github.io/jekyll-pithy).

1. **Fork this repository.**  If you're logged into GitHub, you can fork the repository by click on the little "Fork" button at the top right.
2. **Change the repository's name.** Bring up the repository's settings by clicking on settings, in the tab bar just below the repository's name, all the way to the right. Change the name from ```jekyll-folio``` to ```[username].github.io```, swapping in your username. You **must** do this or GitHub won't recognize this as your website. Now that you've forked the repo and renamed it, the blank site should now be live at your ```[username].github.io``` site. (Although you may need to give it a brief minute to build.)
3. **Download the repository.** Once you've done that, on the main repository page, click on the button that will download the repository into GitHub desktop. It's not labeled, but it's immediately to the left of the "Download ZIP" button. It should look something like this: <span class="ocitcon octicon-desktop-download">...</span> This will automagically open GitHub desktop, asking you to choose where to put your local working copy of the repo. ```git/[username].github.io``` is as good a place as any.
4. **Edit the config file.** You will need to do this just once, thankfully. Open the site by right-clicking on the repo in GitHub desktop and selecting "Open in Atom." Atom will open a new window, which will include a list of files on the left hand side. Below the folders, but above the other files, you'll find ```_config.yml```. Open the file by clicking on it (just once; no need to double click). I've prepared ```_config.yml``` so that it's clear what you need to change and what you don't. At minimum, give your site a ```title```, ```description```, a ```url``` that is http://[username].github.io, and a ```github_username``` that is your GitHub username (case sensitive). Some Jekyll templates come with a motto, others ask for a Twitter handle (which is optional).

**GitHub workflow note:** Once you've made the changes to ```_config.yml```, save the changes in Atom, then switch back over to GitHub Desktop and commit the change, calling it "Initial config" or something.

5. **Edit the About page.** You'll be able to change this easily, whenever you like. Put something in there, even if it's silly or banal. Leave the "YAML front matter" alone, since you're leaving things as is. Write it in Markdown! (NB: YAML stands for YAML Ain't Markup Language, which is a dumb programmer joke: it's recursive, see!) Once again, once you've made your changes, save the file, switch over to GitHub desktop and commit the changes ("Add about").
6. **Add any additional pages**. If you want to add any additional pages—not blog posts!—you may do so by copying, renaming, modifying, and committing the ```page.md``` file. (Shortest way to get started right-click on ```page.md``` in the Atom file browser, select "Duplicate," choose a name for the page, and edit away.)
  7. **Sync the local changes up to GitHub.** Once you've made all the local changes in the steps above and committed them to the master branch of your specially-named github.io repo, press the Sync button at the top right of the GitHub desktop window. That will send your changes to GitHub desktop, and GitHub will build up a special Jekyll site just for you.

### Now start blogging!
Now you're ready to start blogging! More fulsome instructions on how to do that can be found in the post template file in your brand new site's ```_posts``` folder. But here are some schematic instructions:
1. Create a file in the ```_posts``` folder, in the form ```2016-mm-dd-post-title.md```, where ```mm``` is the two-digit month and ```dd``` is the two-digit day, e.g. ```2016-01-14-first-post.md``` for a post the first day of class. **It is important to maintain the proper naming convention for post files, most especially the date convention, beginning with ```yyyy-mm-dd-```.**
2. Begin the file with the appropriate YAML front matter:
```yaml
---
layout: post
title: First Post
description: A first post.
categories: blogging
---
```
The description and categories are optional.
3. Write the post in markdown below the front matter.
4. Save the changes, commit them, and sync the repo to GitHub. Voilà! The post should be live. (It may take a minute or two for GitHub to finish building your changes.)

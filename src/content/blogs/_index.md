+++
date = "20 Jan 2026"
draft = false
title = "Class Blogs"
author = "David Evans"
+++

<!--split-->

# Blogging Mechanics

I believe each team has at least a few members with enough experience using git and web contruction tools that following these instructions won't be a big burden, but if not, it is also worthwhile to learn how to easily set up a free website using github pages. 

- Install [Hugo](https://gohugo.io/).  Hugo is a static website
  generator that builds a site from Markdown pages.  With homebrew on
  Mac OS X, this is easy: `brew install hugo`. (From what I've heard, people are also able to use Hugo on linux and Windows without much difficulty, but I have not tried this myself.)

- [Fork the github repository for the course website](https://github.com/aihumanityclass/aihumanityclass.github.io/fork).  This is what is used to build the
  [https://aihumanityclass.github.io/](https://aihumanityclass.github.io/) site.  One of the members of the blogging team should do this, and then add write permissions for everyone to the forked repository so everyone on your team can contribute to it.

- Copy the `src/content/blogs/template.md` file to create a new `src/content/blogs/class[n].md` file. 

- Update the header section (between the `+++` marks), including the title and author. Don't forget to **update the date** so your page will
  appear in the right order. 

- Replace everything after the header with your content.  

- If you have images or other content to incorporate in your page, store these in the `src/content/static/images` or `src/content/static/docs`. If you have more than a few images, you should create a new subdirectory for your content there. Using images and other resources to make your post interesting and visually compelling is
  highly encouraged!
   
- Write the blog page using Markdown.  Markdown is a simple markup
  language that can be used to easily generate both HTML and other
  output document formats.  You can probably figure out everything you
  need by looking at template, but for a summary of Markdown,
  see [Markdown: Syntax](https://daringfireball.net/projects/markdown/syntax).

- You can incorporate latex math into your markdown. Use `\\(` inline `\\)` for inline math, e.g., `\\( J_{min}\\}` and `$$ ... $$` for display math.

- Your post should include credits for any external materials you use,
  especially for any images you incorporate that you didn't produce.

- Please include full references to the papers, and links to the most
  definitive source available (usually this is to arxiv or a
  conference site, but could be the author's page). You should include
  additional links to relevant and useful reference or code
  repositories. Its good to have an overview section at the beginning
  of the post with links to all the main papers covered, and then to
  have links in specific sections to what is being covered.

- To test the post, run `make develop` (in the `src/` subdirectory of
  your repository).  This starts the Hugo development server, usually
  on port 1313 (unless that port is already in use).  Then, you can
  view the site with a browser at `localhost:1313`.

- When you are ready, submit a pull request to incorporate your
  changes into the main repository (and public course website).  I will probably notice the pull request, but please also send a message to me, so I know the post is ready to review.  At this stage, I will probably make some requests for improvements, and then will post the edited version to the course site.


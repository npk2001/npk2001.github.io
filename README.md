# This is my first marked lab exercise!!!
This lab exercise consists of 10% of my final grade.

## Lab1
**PART 1**
## _Github Pages_
- Create a *GITGUB* **Repository** consisting of a **`Readme.md`** file ("MD" stands for a markdown file)
- Name the **Repository** with your *GITHUB* "username" followed by "github.io".
- Create an index.html page and inpur the **HTML** markup in the *GITHUB* text editor. 
  - Make sure that you always commit a file if there are any changes been made. 
  - Always add a description to the changes been made at the bottom.
- *Congrats*, we have built our first *GITHUB PAGES SITE*.
  - [Link to my page.](https://npk2001.github.io/)

**PART 2**
## _Jekyll & Github Pages_
- Created a .gitignore file which tell Git to ignore the "_site directory that Jekyll automatically generates eah time we commit. 
- Created a _config.yml file which tell jekyll some basic information about the project, in this project we will be telling jekyll what is our site name and the version of "Markdown" we will use. 
- Created a _layout directory which will include 2 different files.
  - First one is a default default.html file where we will store out default **HTML** layout.
  - Post.html file to store the detauls blog post layout - `refer to PART 3 for further details`.
- Furthermore, we moved all the markup from index.html to defaul.html to create a main default template. 
- Note that the "page title" & "content" in the default file is what jekyll calls "*liquid tags"".
- Than we updated our index.heml to use the default layout "`layout: default`".

**PART 3**
## _Blog_
- First create a new layout for your blog post called post.html in the _layout folder.
- Also create a new folder to store all the posts `_post`.
- Please be carefull as Jekyll is very strict with the formate of how the files are named. The formate is `YYYY-MM-DD-title-of-your-post.md`.
- Note that these files use markdown as a markup language which is very similar to plain text. Markdown syntax used in these files gets converted to HTML by Jekyll.
  - [Markdown cheatsheet.](https://packetlife.net/media/library/16/Markdown.pdf)
- Create a blog directry with anindex.html file. We will use a loop to create an unordered list of our blog posts. 
  - [Link to my blog page.](https://npk2001.github.io/blog/)
- As jekyll does not include the blog directory in the "URL" we can control the primalink by adding it to the `_config.yml` file. In this project we add a primalink format of `permalink: /blog/:year/:month/:day/:title`.
  - [Live Blog Post.](https://npk2001.github.io/blog/2021/09/30/site-launched)
- Finally create an about directory with an index.html file and include the default layout tag, this will create an "About" page. 
  - [Link to my About Page.](https://npk2001.github.io/about/)

### That is the end to our Lab 1 assignment ###

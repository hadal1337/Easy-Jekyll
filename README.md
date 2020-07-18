# Easy Jekyll

**Easy Jekyll is using the latest Jekyll version: v1.4.1**

**Jekyll** is an open source static site generator that's perfect for your GitHub page ([demo](https://hulka1337.github.io/)).

**Easy Jekyll** makes it easier to create your blog, by eliminating a lot of the upfront setup, especially for Windows users as Jekyll doesn't support Windows.

- You don't need to touch the command line
- You don't need to install/configure ruby, rvm/rbenv, ruby gems
- You don't need to install runtime dependencies like markdown processors, Pygments, etc
- It's easy to try out, you can just delete your forked repository if you don't like it

In less than 5 minutes, you'll be ready with a minimalistic responsive blog like the one below:

<details>
  <summary>Click to see image!</summary>
  

![Image](https://i.imgur.com/boPPb4F.png)
</details>

## Getting started

### Step 1) Fork Easy Jekyll
Then rename the repository to yourgithubusername.github.io (don't include https://).

### Step 2) Customize and view your site
In _config.yml file, on line 28, add https://yourgithubusername.github.io in the "" quotation.

Enter your site name, description, email and many other options by editing the _config.yml file.

Making a change to _config.yml (or any file in your repository) will force GitHub Pages to rebuild your site with jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it a few more minutes as GitHub suggests and it'll appear soon.

> There are 3 different ways that you can make changes to your blog's files:

> 1. Edit files within your new username.github.io repository in the browser at GitHub.com (shown below).
> 2. Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io). It's optimized for use with Jekyll making markdown editing, writing drafts, and uploading images really easy.
> 3. Clone down your repository and make updates locally, then push them to your GitHub repository.

### Step 3) Publish your first blog post

Edit `/_posts/2020-07-13-welcome-to-jekyll.md` to publish your first blog post. This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

> You can add additional posts in the browser on GitHub.com too! Just hit the + icon in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Local Development

1. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
2. Clone down your fork `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Serve the site and watch for markup/sass changes `bundle exec jekyll serve --livereload`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

## Easy Jekyll Features

- Command-line free _fork-first workflow_, using GitHub.com to create, customize and post to your blog  
- Fully responsive and mobile optimized base theme
- Unlimited creative potential: ([example](https://hadal1337.github.io/))  
- Markdown style blogging  
- SVG social icons for your footer  
- No installing dependencies  
- No need to set up local development  
- *More time to work on other things*

## Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.

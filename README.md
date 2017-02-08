# Beautiful Jekyll

**Beautiful Jekyll** is a ready-to-use template to help you create an awesome website quickly. Perfect for personal blogs or simple project websites.

### Table of contents

- [Prerequisites](#prerequisites)
- [Build your website in 3 steps](#build-your-website-in-3-steps)
- [Add your own content](#add-your-own-content)
- [Last important thing: YAML front matter ("parameters" for a page)](#last-important-thing-yaml-front-matter-parameters-for-a-page)
- [Features](#features)
- [Creating a User Page vs a Project Page](#creating-a-user-page-vs-a-project-page)
- [Showcased users (success stories!)](#showcased-users-success-stories)
- [Advanced: local development](#advanced-local-development-using-docker)
- [Credits and contributions](#credits)

## Prerequisites

- In order to begin the website creation process it is mandatory to create a GitHub account. In order to create an account you can click on this link. [sign up here](https://github.com/join). If you choose to name your website with the username `nadeld` then your website will be `http://johnsmith.github.io`.  
-

## How to create a website

On GitHub, if you go to my repository, there should be a *Fork* button on the top right corner. The reason you should fork this is so that you can copy my website as a template for your own use. Once you fork my repository, you should go into your settings (the cog icon in the top-right corner). By renaming your repository you will have your own unique <yourusername>.github.io website. In addition, you should clone the repository using SSH. In terminal, you should then type the command "bundle install --path ~/.gem" and wait around 5-10 minutes for your website to install. After it is finished, I would type the command "http://127.0.0.1:4000" to check if your website is up and working.

Edit the `_config.yml` file to change all the settings to reflect your site. To edit the file, click on it and then click on the pencil icon (watch the video tutorial above if you're confused).  The settings in the file are fairly self-explanatory and I added comments inside the file to help you further. Any line that begins with a pound sign (`#`) is a comment, and the rest of the lines are actual settings.

After you save your changes to the config file (by clicking on *Commit changes*) your website will be ready-to-use at `http://<yourusername>.github.io`.


Many personalization settings in `_config.yml`, such as setting your name and site's description, setting your avatar to add a little image in the navigation bar, customizing the links in the menus, customizing what social media links to show in the footer, etc.


By default, all blog posts will have buttons at the bottom of the post to allow people to share the current page on Twitter/Facebook/LinkedIn.  You can choose to enable/disable specific social media websites in the `_config.yml` file. You can also turn off the social media buttons on specific blog posts using `social-share: false` in the YAML front matter.

Beautiful Jekyll automatically generates a simple RSS feed of your blog posts, to allow others to subscribe to your posts.  If you want to add a link to your RSS feed in the footer of every page, find the `rss: false` line in `_config.yml` and change it to `rss: true`.

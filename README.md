# Beautiful Jekyll

**Beautiful Jekyll** is a ready-to-use template to help you create an awesome website quickly. Perfect for personal blogs or simple project websites.

### Table of contents

- [Prerequisites](#prerequisites)
- [How to create a website](#How-to-create-a-website)

## Prerequisites

- In order to begin the website creation process it is mandatory to create a GitHub account. In order to create an account you can click on this link. [sign up here](https://github.com/join). If you choose to name your website with the username `nadeld` then your website will be `http://nadeld.github.io`.  

## How to create a website

On GitHub, if you go to my repository, there should be a *Fork* button on the top right corner. Forking my website provides you with a copy of my website as a template for your own use. Once you fork my repository, you should go into your settings (the cog icon in the top-right corner). By renaming your repository you will have your own unique <yourusername>.github.io website. In addition, you should clone the repository using SSH. In terminal, you should then type the command "bundle install --path ~/.gem" and wait around 5-10 minutes for your website to install. After it is finished, I would type the command "http://127.0.0.1:4000" to check if your website is up and working. By editing the `_config.yml` file you can change all your settings to reflect how you want your site to look. To edit the file, click on it and then click on the pencil icon. Any line that begins with a pound sign (`#`) is a comment, and the rest of the lines are actual settings. After you save your changes to the config file (by clicking on *Commit changes*) your website will be ready-to-use at `http://<yourusername>.github.io`.
By default, all blog posts will have buttons at the bottom of the post to allow people to share the current page on Twitter/Facebook/LinkedIn.  You can choose to enable/disable specific social media websites in the `_config.yml` file. If you do not want to share your social media accounts you can go into the `_config.yml` and choose which ones to remove by using `social-share: false`.

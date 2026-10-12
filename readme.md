# Stellar Clicker Website

> [!WARNING]
> Archived and no longer maintained; kept for reference. Written in 2016 for Laravel 5.2 and PHP 5.5, and bundles a beta version of Flarum. All of these are end-of-life, and the site (stellar.polymorphixgaming.com) is no longer online.

## Overview

The website, blog, and forum for [Stellar Clicker](https://github.com/angiebrr/um-csci412-stellar-clicker), a clicker game my team made for CSCI 412 at the University of Montana in spring 2016.

**Tech:** PHP 5.5, Laravel 5.2, Sentinel, jQuery, LESS, Bootstrap, Gulp, Flarum (beta), MariaDB, Mailgun, CentOS 7

### What I built

- The Laravel app: routes, models, schema, seeders, Blade views, JavaScript, and LESS
- Authentication with Sentinel
- A developer blog where bloggers post in Markdown and readers can comment
- A Flarum forum in `flarum/`, with plugins like image uploads and media embeds and a theme adjusted to match the main site
- The CentOS 7 server it ran on, down to the virtual hosts for each subdomain

Matthew Dolan filled in some of the blog and user management controllers, and he tried out several self-hosted wikis before we settled on a Wikia page embedded in an iframe.

## Screenshots

![The home page, with download links and the developer blog](docs/images/home-page.jpg)

![A blog post's comment thread](docs/images/blog-comments.jpg)

![The Flarum forum](docs/images/forum.jpg)

<details>
<summary>More screenshots</summary>

![The lower half of the home page, linking to the forum and wiki](docs/images/home-page-2.jpg)

![A developer blog post](docs/images/blog-post.jpg)

![A blog post with an embedded video](docs/images/blog-video-post.jpg)

![The Markdown post editor](docs/images/post-editor.jpg)

![Managing blog posts](docs/images/manage-posts.jpg)

![Managing users (seeded test accounts)](docs/images/manage-users.jpg)

![Editing a user's settings and roles](docs/images/edit-user.jpg)

![The login and registration page](docs/images/login-register.jpg)

![A forum category](docs/images/forum-category.jpg)

![Flarum's extension settings](docs/images/forum-extensions.jpg)

![The embedded Wikia page](docs/images/wiki.jpg)

</details>

<h1 align="center">
  AnimeCode - Watch High Quality Anime Online, No Ads!
</h1>

<p align="center">
  A PHP web application used for browsing, searching, and fetching anime details and episodes.
</p>

<h2> Table of Contents </h2>

- [Note](#note)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
  - [Locally](#locally)
  - [Docker](#docker)
  - [Heroku](#heroku)
  - [Vercel](#vercel)
  - [Render](#render)
  - [Railway](#railway)
- [Sponsor](#sponsor)

## Note

- This is an **Educational** Project, purely made for learning purposes.
- We do **NOT** promote piracy or free anime streaming sites.

<hr />

**This is old source of https://animecode.com**

This is an improved version of Anikatsu - Base code of this repo. New source code of AnimeCode.com will not be public anytime soon.

## Features

- ✔ Requires no database.
- ✨ No Annoying Video Ads.
- 🎁 Recent released, popular, sub, sub, trending, A to Z list.
- ✔ WatchList local storage functions.
- 🎉 Stream in 1080p, 720p, 480p, and 360p.
- ⚡ Supported Devices: PCs, Laptops, Tablets, Android and iOS mobile, smart TVs.
- 🎨 Responsive Design and SEO optimized.
- 🏆 Auto Image Optimization to webp.
- ⭐ Anime Available Based on Genres, Seasons, categories, status, language.
- 🚀 Ready to deploy code.

## Requirements

- A PHP web server hosting.
- A domain for the website.
- Deploy [Zia API](#api).
- Deploy [Consu API](#api).
- First deploy the [API REPO](https://github.com/warlordsnet/zia-api). Deploy It and Update the `$api` variable in `_config.php` with a new URL.
- Also deploy this [API repo](https://github.com/warlordsnet/consu-api) if you want the trending section and banner.
- PHP environment or directly upload the code on PHP supported hosting.
- Deploy the [CDN repo](https://github.com/warlordsnet/cdnzia) and add its URL in `_config.php`.

- **To Update Website Info (Website name, logo, favicon, socials URL) Edit `_config.php` file.**

<hr />

## Domain

Purchase a domain from ambitionhost.in, namecheap, or godaddy. If you don't know what to do about the domain, search Google on how to buy a domain and add Cloudflare to it.

If you try a free hosting given below, you will get a free sub-domain from them. You can also get a free domain from FREENOM - search Google on how to get a Freenom domain.

## Hosting

**Only for testing**

You can try these free hosting providers for demo or testing. Do not use these as your own because these are slow.

- [InfinityFree](https://www.infinityfree.net/)
- [ProFreeHost](https://profreehost.com/)
- [000Webhost](https://in.000webhost.com/free-php-hosting)

**Important & required**

Buy PHP hosting from ambitionhost.in (cheap), hostinger.in, bluehost.in, or godaddy. If you have purchased a domain, search Google on how to add the domain to cPanel hosting.

Once you have purchased Cpanel from hosting provider then follow these:
- Login to your Cpanel > Open file manager.
- Open `public_html` (some Cpanel may have `htdocs` instead of `public_html` so follow the same steps).
- Upload the files of this repo in the `public_html` directory.
- Configure domains from cPanel and the site is ready ✨

## Local Deployment

First download the repository using. After cloning, change the repo name to your site name.

```sh
git clone https://github.com/normalhuman01/animecode.com
cd animecode.com

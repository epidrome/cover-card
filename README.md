# Cover Card landing page theme

## Quick set-up

1. [Use this template](https://github.com/epidrome/cover-card/generate)
2. Edit the `_config.yml` with your online presence accounts and upload a background and an avatar image
3. Go to `Settings`, scroll down to `Github Pages` and find your new home page link

## Dependencies

This theme is based on [jekyll](https://jekyllrb.com/) and [jekyll-remote-theme](https://github.com/benbalter/jekyll-remote-theme). The above dependencies are natively supported by [Github Pages](https://pages.github.com/), which will build and deploy your site as soon as you make any change to your files. The theme is also based on the icons from [Font Awesome](https://fontawesome.com/). 

## Motivation

Create a cover page for your social media profiles, host it for free on Github Pages, and maintain it in minutes, not hours. [Demo](https://epidrome.github.io/cover-card)

This theme is ideal for people or organizations who are busy enjoying their life or business and who want a simple business card for their online presence.

Please keep this README file because it contains the credits at the end and it might become handy after you have completely forgoten the set-up instructions.

## Design rationale

The design rationale of this theme is to do less than other themes: "Less is more"

The majority (99%) of the availabe jekyll themes offers a blog, but I have never been able to keep blog content (or its technology) updated over time.

Let's be honest with ourselves: How does an (abandoned) blog centered web site look to new visitors if we have not posted since two years ago?

## Make it yours

[Fork this repository](https://github.com/epidrome/cover-card/fork) and edit the files to your liking: As a first step, you may want to replace the images and edit the `_config.yml` with your online profiles. You can test the result almost in real-time at the `Github Pages` section in the Settings tab (gh-pages branch).

### Avatar or Logo

The avatar image should be square and at least 200 pixels. Chances are that you have a selfie somewhere in your media storage. If you are making a page for a business or product, then use a logo.

### Background image sets the mood

There is no aspect ratio requirement for the background image, but it should be big enough for contemporary (desktop, tablet, phone) computer displays and dark enough in order to work for the white foreground text and icons.

### Social profiles

Edit the `_config.yml` file with your social media profiles by adding the respective account name, according to the documentation and comments inside that file. You can delete or comment out the social media that you don't need. Since v04, you can also control the order of your social media accounts. Moreover, you can add new media accounts and choose the icon.

### Domain name

Github Pages supports free custom domain names, so it is worth buying a domain name and fill it in `Custom domain` field at the settings. If you want to use the theme with you user page (ie. username.github.io), then delete (or rename) your `master branch` and rename your `gh-branch` to `master` [#13](https://github.com/epidrome/cover-card/issues/13)

### Working example

In addition to the configuration file in this repository, you can also [inspect a modified example of the configuration file](https://github.com/epidrome/home/blob/master/_config.yml), which is currently using the previous version of the theme.

### Updates

Please note that the theme is currently in beta, so some updates at the [master branch](https://github.com/epidrome/cover-card/tree/master) might break your site. Don't panic! 

If you wish to keep your theme frozen and not receive updates, then you can [revert your remote_theme to the last known good configuration](https://github.com/benbalter/jekyll-remote-theme):

> You may also optionally specify a branch, tag, or commit to use by appending an @ and the Git ref (e.g., epidrome/cover-card@v0.3). If you don't specify a Git ref, the master branch will be used.

Please note that currently Github Pages seems to build your site only when you make a local change. This means that the theme might get updated but you will not receive the updated version unless you make a local change in your forked repository.

You can always visit [releases](https://github.com/epidrome/cover-card/releases) for new features and check [issues](https://github.com/epidrome/cover-card/issues) for major bugs.

### Expert options

You can find and locally overide advanced options (custom domain name, extra social icons, font styles) for this theme in the documentation (readme) at the [master branch](https://github.com/epidrome/cover-card/tree/master).

## Credits

This page is based on the [cover-card jekyll remote theme](https://github.com/epidrome/cover-card/tree/master).

Background photo by Anders Jildén and avatar photo by Ayo Ogunseinde, both on [Unsplash](https://unsplash.com/)

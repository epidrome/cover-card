# Cover-card jekyll theme

The aim of this theme is to remain simple and updated. As Antoine de Saint-Exupery said:

> Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.

## Design

The design of this theme is defined by the following features that IT DOES NOT HAVE:

### Blog

I love blogs. I have been making and following blogs since blogs existed in the early 2000s. The reality is that the vast majority of the blogs back then do not exist anymore. I can safely predict that the vast majority of the blogs that are around nowadays will not exist soon, even the popular ones.

Don't get me wrong: Jekyll is an excellent system for making blogs, but your main web site should not be build around a blog. A blog is just an add-on to your main site that should be easy to turn off, or to switch to the next great blogging platform, system, or social media profile that supports blogging. Even [the father of jekyll](http://tom.preston-werner.com/) is not blogging very much over the years, then why have the blog at the center of the online presence. A blog is nice to have but it is not a must have.

I understand that a jekyll theme without a blog might sound like a self contradiction, but jekyll has also motivated something even more useful than itself: seamless hosting with Github Pages. This theme takes advantage of both jekyll and Github Pages, in order to create something similar to [about.me](https://about.me/), without the price tag.

### Folders and files



## Implementation

[A working example](https://epidrome.github.io/cover-card) demonstrates that the new [jekyll remote theme](https://github.com/blog/2464-use-any-theme-with-github-pages) functionally efficiently separates content from presentation, so you can keep in your repository only the custom assets, e.g., images, configuration, while the remote theme seamlessly takes care of the beatifully simple presentation.

In this way, you will receive future updates without pulling and resolving conflicts from the main theme. In the case that you don't like a particular update (e.g. font change, or font size), you can always [revert your remote_theme to the last known good configuration by pointing to a particular commit](https://github.com/benbalter/jekyll-remote-theme). Moreover, it becomes easier to switch to other similar themes.

### Set-up for end-users

Just fork the [default repository](https://github.com/epidrome/cover-card), which has been set to be the gh-pages one, because it makes it easier for average users to fork and use.

### Set-up for development

This theme is easier for new jekyll users to fork and use. One side effect of this choice is that it is harder for advanced users to contribute, but this should not be a problem for the expert user.

1. git clone https://github.com/epidrome/cover-card.git
2. cd cover-card
3. git checkout master
4. git pull

Then you can test the theme on gh-pages and develop new features on master branch.

## Contributing

Fork this repository and submit a pull-request for a bug or an improvement at the **master branch**.

## Credits

Credits and inspiration for this theme go to [front cover theme](https://dashingcode.github.io/front-cover/), jekyll remote theme, and being lazy to keep my web page updated with the latest standards and trends.

# Cover-card jekyll theme

The aim of this theme is to remain simple and updated. As Antoine de Saint-Exupery said:

> Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.

## Design

The design rationale of this theme is to do less than other themes: "Less is more"

The majority (99%) of the availabe jekyll themes offer a blog, but I have never been able to keep a blog content (or its technology) updated over time. Let's be honest. If you want a blog choose a theme that is focused on the blog.

## Implementation

[A working example](https://epidrome.github.io/cover-card) demonstrates that the new [jekyll remote theme](https://github.com/blog/2464-use-any-theme-with-github-pages) functionally efficiently separates content from presentation, so you can keep in your repository only the custom assets, e.g., images, configuration.

In this way, you will receive future updates without pulling and resolving conflicts from the main theme. In the case that you don't like a particular update (e.g. font change, or font size), you can always [revert your remote_theme to the last known good configuration by pointing to a particular commit](https://github.com/benbalter/jekyll-remote-theme). Moreover, it becomes easier to switch to other similar themes.

### Set-up for a new computer

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

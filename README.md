# Subsurface GitHub Pages

While this isn't ready to replace our full website, it's a start to make
sure we get better announcements and to make it easier for people to
translate those announcements.

For now this is very much work in progress...

Things to note:

- posts go into the `_posts` folder in each language folder, so for example `de/_posts`
- pages go into the language folder, with the exception of the English pages which are in the root folder
- we have a convenient reusable block for downloading binaries at `_includes/desktop-release-bottom.MD` which uses the {{page.version}} tag from the front matter of the page that includes it - this one I decided to translate inside a single file instead of having multiple versions
- it's easy to test this locally - https://help.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll

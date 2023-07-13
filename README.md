# Gitea-Pitch-Black

Pitch black theme for Gitea versions 1.14 through 1.18
From version 1.19, [gitea removed](https://github.com/go-gitea/gitea/pull/23508) the `less` files for `css` files

## Use cases

1. Use `theme-pitchblack.less` to create theme at compile time. Drop this file into gitea/web_src/less/themes and compile Gitea!
2. Use `theme-pitchblack.css` for a de-minified version of the css that can easily be edited for personal use. Just drop this file into `/path/to/gitea/custom/public/css` and add the new [theme into your app.ini](https://docs.gitea.io/en-us/config-cheat-sheet/#ui-ui) file.
3. Use `theme-pitchblack.less` to compile theme using another method like [clessc](https://github.com/iamdoubz/Gitea-Pitch-Black/issues/6), you will also need the [dark.less chroma dependency](https://github.com/go-gitea/gitea/tree/main/web_src/less/chroma/dark.less) directly from the Gitea repo.

## Photos

[![pitchblack01.md.png](https://pix.dou.bet/images/2021/06/28/pitchblack01.md.png)](https://pix.dou.bet/image/gUOb)
[![pitchblack02.md.png](https://pix.dou.bet/images/2021/06/28/pitchblack02.md.png)](https://pix.dou.bet/image/gFN8)
[![pitchblack03.md.png](https://pix.dou.bet/images/2021/06/28/pitchblack03.md.png)](https://pix.dou.bet/image/gAoV)

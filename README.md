# Gitea-Pitch-Black

Pitch black theme for Gitea versions 1.14 through 1.18
From version 1.19, [gitea removed](https://github.com/go-gitea/gitea/pull/23508) the `less` files for `css` files

## Use cases

1. Use `theme-pitchblack.less` to create theme at compile time. Drop this file into gitea/web_src/less/themes and compile Gitea!
2. Use `theme-pitchblack.css` for a de-minified version of the css that can easily be edited for personal use. Just drop this file into `/path/to/gitea/custom/public/css` and add the new [theme into your app.ini](https://docs.gitea.io/en-us/config-cheat-sheet/#ui-ui) file.
3. Use `theme-pitchblack.less` to compile theme using another method like [clessc](https://github.com/iamdoubz/Gitea-Pitch-Black/issues/6), you will also need the [dark.less chroma dependency](https://github.com/go-gitea/gitea/tree/main/web_src/less/chroma/dark.less) directly from the Gitea repo.

## Photos

[![gitea dashboard with code contributions](https://github.com/iamdoubz/Gitea-Pitch-Black/assets/4871781/b97eab0f-f948-4526-9fee-1340599ce97e)](https://pix.dou.bet/image/gUOb)
[![gitea main profile page](https://github.com/iamdoubz/Gitea-Pitch-Black/assets/4871781/a3bf4086-6a04-41f0-be69-ca535d8b4249)](https://pix.dou.bet/image/gFN8)
[![gitea single repo page](https://github.com/iamdoubz/Gitea-Pitch-Black/assets/4871781/19656fb0-1408-4e57-9245-24d2f61ea958)](https://pix.dou.bet/image/gAoV)

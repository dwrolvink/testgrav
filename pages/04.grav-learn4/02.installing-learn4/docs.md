---
title: 'Installing & Configuring Learn4'
taxonomy:
    category:
        - docs
page-toc:
    active: true
---

bla
### Getting the files
bla
### Installation
bla
### Configuration
You'll need to install a couple of packages to get the Learn4 theme to appear as in the offical doc.

#### Prism
Install Prism Hightlighter via the admin panel, and enable it. Disable the plugin called `Highlight`, as it messes up the linenumber rendering.
Set linenumbers to enabled. I have `Prism Base16 Flat Dark Css` as theme.
Then, you can get something like:

```powershell
Write-Error "prompt not found!"
```

```bash
git push
```
You'll have to set a different class for different languages. You can find the list of supported classes [on their git](https://github.com/trilbymedia/grav-plugin-prism-highlight#languages-included). There's also a lot more options that you can add. Note that this code does not work on GitHub.
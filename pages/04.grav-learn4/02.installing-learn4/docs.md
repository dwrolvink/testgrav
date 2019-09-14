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
Install Prism Hightlighter via the admin panel, and enable it. Set linenumbers to enabled. I have `Prism Base16 Flat Dark Css` as theme.
Then, you can use the following in your code:
```bash
[`prism classes="language-bash"] git push [/prism]
```

to get

[prism classes="language-bash command-line"] git push [/prism]

You'll have to set a different class for different languages. You can find the list of supported classes [on their git](https://github.com/trilbymedia/grav-plugin-prism-highlight#languages-included).
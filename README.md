# Macaron-rstheme

## Template source:https://github.com/Xiaoyang-Song/RStudio-Theme-Customization

## References:
1. https://github.com/Xiaoyang-Song/RStudio-Theme-Customization
2. https://github.com/batpigandme/night-owlish
3. https://c.runoob.com/front-end/6214/#77817b
4. https://rstudio.github.io/rstudio-extensions/rstudio-theme-creation.html#creating-a-tmtheme
5. https://tmtheme-editor.glitch.me/#!/editor/theme/Monokai


This is an Rstudio theme that is not yet completely satisfactory, but can be used with some effort, inspired by a game character Kyouyama Kazusa.


![杏山カズサ](https://github.com/Kyouyama-Kazusa/Macaron_rstheme/blob/main/kazusa.jfif)


![Example](https://user-images.githubusercontent.com/127744117/225313248-f1695d8a-ee0c-449c-92bc-ba9cbdda7e58.png)


By the way, remember if you want to modify the color of the operators. The color of the operators is not included in the global variable in the author's template.
```
.ace_keyword:not(.ace_operator),
.ace_meta,
.ace_storage,
.ace_storage.ace_type,
.ace_support.ace_type {
  color: <your color>;
}
```

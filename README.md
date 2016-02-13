# Misc design features for JavaScript & R

### Color-blind friendly palette

These colors are color-blind friendly and look good as gray scale (black-and-white).

#### HEX Values

```
    # Black, greenish, orangish, lightblue,
    # navy?, darkorange, pink-kinda, yellow!
    #000000
    #009E73
    #e79f00
    #9ad0f3
    #0072B2
    #D55E00
    #CC79A7
    #F0E442
```

#### R Code

```
    truColors <- c("#000000", "#009E73", "#e79f00", "#9ad0f3", "#0072B2", "#D55E00",
                    "#CC79A7", "#F0E442")

    # Example:
    plot(x, y, col = truColors[3])
    plot(foo, bar, col = truColors[4])
```

### JavaScript Docs

Using [JSDocs](https://github.com/jsdoc3/jsdoc) to include function and in-line documentation of JavaScript code.

Install latest version via npm:

```
    npm install jsdoc
```

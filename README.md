![Vesper Preview](/preview.png)

# Vespertino Black

<a href="https://marketplace.visualstudio.com/items?itemName=herfave.vespertino-black"><strong>Install →</strong></a>

**Vespertino Black** is based on [Vespertino](https://github.com/cstrlcs/vespertino), which is based on the great theme [Vesper](https://github.com/raunofreiberg/vesper) by [Rauno Freiberg](https://rauno.me). It is a Peppermint and orange flavored dark theme for VSCode.

I've forked Vespertino to use black backgrounds to make better use of my OLED monitor.


## Changes
- **Made everything black**
- New color for type declarations
- Bold for function calls, declarations and HTML tags
- Italic for comments and keywords
- Some small tweaks

## Fonts (Optional)

The fonts Lucas used in the preview are [Fira Code](https://github.com/tonsky/FiraCode) and [Victor Mono](https://rubjo.github.io/victor-mono/).

Sadly, VSCode doesn't support multiple fonts right now. You can use `Victor Mono` alone for a similar effect.

If you really want to mix fonts, you can use [this extension](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) to inject this line of CSS into your VSCode:

```css
/* Changes the font only for the italic part of the code. */
.mtki {font-family: 'Victor Mono';}
```

> Beware that adding custom CSS is a hack and it is optional. Use it at your own risk.~~

## Credits

- [Lucas Castro](https://github.com/cstrlcs) for the token highlighting
- [Rauno Freiberg](https://rauno.me) for the Vesper theme.

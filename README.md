# Usage:

After downloading the `.woff`, `.woff2`, and `.ttf` create a new `.css` file, and write

```css
@font-face {
  font-family: "REPL-SDTIN Default";
  src: url("./REPL-SDTIN Default.woff") format("woff"), url("./REPL-SDTIN Default.woff2")
      format("woff2"), url("./REPL-SDTIN Default.ttf") format("truetype");
}
```

in it.

Then in the html file link the css file using

```html
...
<link rel="stylesheet" href="YOUR_CSS_FILE.css" />
...
```

You can define the fonts for certain elements by doing

```css
...
YOUR_ELEMENT {
  ...
  font-family: 'REPL-SDTIN Default';
  ...
};
...
```

---

&gt;&copy; Created by theiocoder ~ 2021 'REPL-SDTIN Default'&lt;

[My Github](https://github.com/theiocoder)

[My Replit](https://replit.com/@iocoder)

Math typesetting using KaTex for gitbooks
==============

This is a fork of the orginal plugin-katex but works with newer versions of gitbook.

### Usage

Inline math is used with double $ signs: 
```
$$ a^2 + b^2 = c^2 $$
```

Block math is used with tripple $ signs: 
```
$$$ \int \frac{1}{1+x^2}\, dx = \arctan x + C. $$$
```

Use it for your book, by adding to your book.json:

```
{
    "plugins": ["enhanced-katex"]
}
```

then run `gitbook install`.


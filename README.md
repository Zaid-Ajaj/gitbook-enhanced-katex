Math typesetting using KaTex for gitbooks
==============

Use it for your book, by adding to your book.json:

```
{
    "plugins": ["enhanced-katex"]
}
```

then run `gitbook install`.

## Usage
Inline math:
```
$$\int_{-\infty}^\infty g(x) dx$$
```

Block math:
```
$$$
\int_{-\infty}^\infty g(x) dx
$$$
```

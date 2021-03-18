# Advanced selectors

### Direct son

Use `>` to select the first son of main selector

```css
main > p {
}
```

### A element after selector

Select just `p` after `img` using `+`

```css
Img + p {
}
```

### All elements after selector

// Select all `p` afeter `img` usinng `\*`

```css
Img \* p {
}
```

### Exclude

// Exclude a tag `p` with id `#mission``

```css
.container p:not(#mission) {
}
```

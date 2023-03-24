# PseudoElements

## Elements refs

### Some Examples

#### First child of list

```css
.items: first-child {

}
```

#### Last child of list

```css
.items: last-child {

}
```

#### 4th element of the list, if use 2n can get the pair elements

```css
.items: nth-child(4) {

}
```

#### get all elements after the 4th element

```css
.items: nth-child(n + 4) {

}
```

#### get all elements <p> after the 4th element

```css
.items: p:nth-child(n + 4) {

}
```

#### Css space can be insert before element

```css
.items: before{
 content: “{”
}
```

#### Css space can be insert after element

```css

.items: after{
 content: “}”

}
```

#### First letter of a string

```css
.title: first-letter {

}
```

#### First line of a string

```css
p: first-line {

}
```

# Canvas Markdown Conversion Test

## Heading with `inline-code`

Paragraph with HTML in inline code `<h2>hi there</h2>`

## Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

## Lists

- Unordered
  - Nested
- List

1. Ordered
2. List

---

1. Item one

   ```rb
   puts "Work please"
   ```

2. Item two

   ```rb
   puts "Work please"
   ```

## Code blocks

JSX:

```jsx
function App() {
  const hi = "there";
  return (
    <div>
      <h1>This is some JSX</h1>
      <p>{hi}</p>
    </div>
  );
}
```

HTML:

```html
<div>
  <h1>This is some HTML</h1>
  <p>hello!</p>
</div>
```

JS:

```js
function hello(world) {
  const hi = "there";
  console.log(hi, world);
}
```

Ruby:

```rb
class Dog
  def initialize
    @name = "Lucy"
  end
end
```

SH:

```sh
json-server --watch db.json
```

text:

```txt
ok then
```

No language:

```
ok then
```

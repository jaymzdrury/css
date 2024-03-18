## CSS

<img src="https://media.istockphoto.com/id/1450698208/photo/number-3-cut-on-note-paper-white-note-paper-blue-background.webp?b=1&s=170667a&w=0&k=20&c=lh4lg9sVHuPSbqyWFE-AlB0QoYhDsJiOgoDMGKCuIIg=" alt="CSS" width="350" />

---

_@container_

container.css

```JavaScript
  <>
    <section>
      <div className="card" />
    </section>
    <div className="card" />
  </>
```

with tailwind

```JavaScript
<body className="@container">
  <section>
    <div className="@xs:w-4/5" />
  </section>
  <div className="@xs:w-4/5" />
</body>
```

_@property_

property.css

```JavaScript
<button />
```

_@scope_

scope.css

```JavaScript
<>
  <h1 class="title">Title</h1>
  <section class="card">
    <h2 class="title">Title</h2>
  </section>
</>
```

_@starting-style_

starting-style.css

```JavaScript
<>
  <button id="toggle">Toggle</button>
  <div class="card">Card</div>
</>
```

_clamp_

clamp.css

```JavaScript
<body>
  <div class="card">Card</div>
</body>
```

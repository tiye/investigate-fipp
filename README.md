
...
----

> trying to figure out why `fipp.edn/pprint` is slow...

### Usage

Create `target/index.html`:

```html
<div>
  Run <code>$runDemo$</code> in Console, it's slow functions. Question is, why slow?
</div>

<script type="text/javascript" src="main.js"></script>
```

And compile ClojureScript:

```bash
yarn
yarn build
yarn serve
```

Visit http://localhost:8080

### License

MIT

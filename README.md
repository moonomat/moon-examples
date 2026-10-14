# Moon examples

Example designs written in **Moon**, a declarative YAML language for parametric 3D,
made for coding agents to write and for people to tweak.
Each `.moons` file is a complete Moon bundle: every source file of a design in one
readable YAML file. The design's own `doc:` at the top says what it is.

## Open an example

Open any `.moons` file here in the Moonomat Viewer by putting its GitHub URL after
`moonomat.com/view?url=`:

https://moonomat.com/view?url=https://github.com/moonomat/moon-examples/blob/main/stairs.moons

Change parameters live, download the .glb, or view it in AR on a phone.
"Remix in Moonomat" opens the source for editing, no sign-up needed.

## Embed on your own page

```html
<script src="https://moonomat.com/embed/v1.js"></script>
<moonomat-viewer src="https://github.com/moonomat/moon-examples/blob/main/stairs.moons"></moonomat-viewer>
```

The language

- Moon language specification (https://moonomat.com/docs/moon-spec)
- All operations (https://moonomat.com/docs/moon-api-spec)

The Moon runtime evaluates a design deterministically and outputs glTF (also SVG, PNG,
JSON). It runs in your browser as WebAssembly.

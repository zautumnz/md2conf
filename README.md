# md2conf

Confluence now has the ability to use Markdown directly, so I'm leaving this
tool to rot. Feel free to fork if you still need this ability for some reason.

---

Markdown to Confluence markup.

Fork of [markdown2confluence](https://github.com/chunpu/markdown2confluence)
with a bunch of patches applied.

## Usage

`npx md2conf < foo.md > foo.conf`, or `npx md2conf foo.md > foo.conf`.

You can install this globally and avoid the extra call to `npx` with `npm i -g
md2conf`.

In Vim, you can rewrite your buffer with `:%! npx md2conf`.

[LICENSE](./LICENSE.md)

# scoop-jlens

The [Scoop](https://scoop.sh) bucket of [jlens](https://github.com/thkprado/jlens), a JSONata
engine with evaluation audits and editor support.

```sh
scoop bucket add jlens https://github.com/thkprado/scoop-jlens
scoop install jlens/jlens
jlens --version
```

The manifest installs the release binary for Windows (x86-64), checked against the
`SHA256SUMS` of each [release](https://github.com/thkprado/jlens/releases). `scoop update jlens`
follows the releases. The first release in this bucket is 0.14.0.

`bucket/jlens.json` is generated: the Scoop workflow of thkprado/jlens replaces it when a
release is published. Do not edit it here; report issues and send changes to
[thkprado/jlens](https://github.com/thkprado/jlens/issues).

See the [installation page](https://thkprado.github.io/jlens/getting-started/installation.html)
for the other ways to install jlens.

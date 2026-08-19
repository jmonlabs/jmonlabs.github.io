# jmonlabs.github.io

The org landing page, deployed at [jmonlabs.github.io](https://jmonlabs.github.io/).

It links out to the four JMON packages and the live REPL; it holds no
library code itself. The REPL's own source is in
[jmon/show](https://github.com/jmonlabs/show)'s `live/` — this repo's
Pages workflow checks that out and assembles it in alongside `index.html`.

```
_site/
  index.html   # this repo's own
  live/        # copied from jmonlabs/show at deploy time
```

## License

GPL-3.0-or-later

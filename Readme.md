# Hooks

GIT hooks that I use, which is really only just one :) a poor-mans CI to ensure your master branch always passes.

## One-liner

```bash
curl -sL https://github.com/tj/hooks/archive/master.tar.gz | tar xz --strip-components=1 -C $(git rev-parse --show-toplevel)/.git/hooks/
```

## Badges

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-stable-green.svg)
[![](http://apex.sh/images/badge.svg)](https://apex.sh/ping/)

---

> [tjholowaychuk.com](http://tjholowaychuk.com) &nbsp;&middot;&nbsp;
> GitHub [@tj](https://github.com/tj) &nbsp;&middot;&nbsp;
> Twitter [@tjholowaychuk](https://twitter.com/tjholowaychuk)

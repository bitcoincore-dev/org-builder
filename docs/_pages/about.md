---
title: "org-builder / about"
author_profile: false
permalink: /about/
title: "bitcoincore-dev"
---

<html>
<head>
  <link rel="stylesheet" href="/assets/css/style.css">
</head>
</html>

## Building environment for jekyll projects

[![CI](https://github.com/bitcoincore-dev/org-builder/actions/workflows/push.yml/badge.svg)](https://github.com/bitcoincore-dev/org-builder/actions/workflows/push.yml)

Install [docker](https://docs.docker.com/get-docker/)	
Install [make](https://www.gnu.org/software/make/)


**then**

```
git clone https://github.com/bitcoincore-dev/org-builder.git ~/org-builder
git clone https://github.com/bitcoin-dot-org/Bitcoin.org.git ~/Bitcoin.org

cd org-builder

SITE=~/Bitcoin.org make image
SITE=~/Bitcoin.org make server
```

--

## License

Distributed under the [MIT License](https://raw.githubusercontent.com/bitcoincore-dev/org-builder/master/LICENSE){: .btn .btn--primary}.

# 0xDomains  <img width="60px" src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif">

A Handy Script for Finding Sub-Domains using google dorks and certspotter.com

# Installation :

From pip :

```bash
pip3 install oxdomains
```

From source :

```bash
git clone https://github.com/0x68616469/oxdomains/
```

### Requirements :

[oxansi](https://github.com/0x68616469/oxansi/)
[oxflags](https://github.com/0x68616469/oxflags/)
[google](https://pypi.org/project/google/)
(downloaded automatically with pip)

# Example :

```bash
oxdomains -u hackerone.com
```

result :

```md
[v] Found 9 subdomains :

- api.hackerone.com
- hackerone.com
- www.hackerone.com
- support.hackerone.com
- docs.hackerone.com
- mta-sts.hackerone.com
- mta-sts.managed.hackerone.com
- mta-sts.forwarding.hackerone.com
- design.hackerone.com
```

# Arguments :


|     | Option          | Description               | Default |
| --- | --------------- | ------------------------- | ------- |
| -u  | --url           | Choose Target URL         |         |
| -a  | --api-key       | certspotter.com API key   | None    |

<hr>

![Follow me](https://img.shields.io/badge/-Follow%20Me-222222?logo=twitter&logoColor=black&color=272838&labelColor=C09891&style=for-the-badge&logoWidth=30&link=https://twitter.com/0x68616469)
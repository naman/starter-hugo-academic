---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'DICE*: A Formally Verified Implementation of DICE Measured Boot'
subtitle: ''
summary: ''
authors:
- Zhe Tao
- Aseem Rastogi
- Naman Gupta
- Kapil Vaswani
- Aditya V. Thakur
tags: []
categories: []
date: '2021-08-01'
lastmod: 2022-05-04T12:19:59-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

url_slides: 'https://www.usenix.org/system/files/sec21_slides_tao.pdf'
url_pdf: 'https://www.usenix.org/system/files/sec21-tao.pdf'

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-04T17:19:58.860865Z'
publication_types:
- '1'
abstract: 'Measured boot is an important class of boot protocols that ensure that each layer of firmware and software in a device’s chain of trust is measured, and the measurements are reliably recorded for subsequent verification. This paper presents DICE*, a formal specification as well as a formally verified implementation of DICE, an industry standard measured boot protocol. DICE* is proved to be functionally correct, memory-safe, and resistant to timing- and cache-based side-channels. A key component of DICE* is a verified certificate creation library for a fragment of X.509. We have integrated DICE* into the boot firmware of an STM32H753ZI micro-controller. Our evaluation shows that using a fully verified implementation has minimal to no effect on the code size and boot time when compared to an existing unverified implementation.'
publication: '*30th USENIX Security Symposium (USENIX Security 21)*'
links:
- name: URL
  url: https://www.usenix.org/conference/usenixsecurity21/presentation/tao
---

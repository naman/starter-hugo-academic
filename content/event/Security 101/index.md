---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Security 101"
event: Tutorial
event_url:
location: Media.net
address:
  street:
  city: Mumbai
  region:
  postcode:
  country: India
summary: The tutorial was conducted for the training session for the new DevOps hires at media.net. 
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-05-04T12:10:38-05:00
date_end: 2022-05-04T12:10:38-05:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2022-05-04T12:10:38-05:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
The talk content was a collaboration with [lionaneesh](https://github.com/lionaneesh). Please find the slides here https://slides.com/aneeshdogra-1/security-101.

# Test

- Solve https://backdoor.sdslabs.co/challenges/XORFUN. (credits: https://backdoor.sdslabs.co/users/rnehra01) [1 point]
- Use a software frontend forward proxy TLS offloader (nginx, haproxy) to host a website.
  - What is end-to-end encryption?
  - You have to use OpenSSL library to generate a local CA, intermediate CA, certs (both server and client) and CRLs.
- Get a cert signed by Letsencrypt CA. [2 points]
- Do the following services use asymm / symm crypto - ssh, tls, bluetooth pairing? How does the key sharing work? [1 point]
- Talk to any one of the senior DevOps to understand how LDAP/ SSO works in media.net. How are your users, created and keys synced accross the servers? [2 points]

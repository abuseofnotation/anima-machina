---
layout: default
---

(Work in progress)
---

*This is a book about my search for truth, in an artificial world.*

*A largely autobiographical work, in which each chapter takes place in roughly 10 years from the last.*

Jencel

{% for post in site.posts reversed %}

[{{post.title}}]({{post.url | prepend:site.baseurl}})
===

{{post.summary}}

{% endfor %}


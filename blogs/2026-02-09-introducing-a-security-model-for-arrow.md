---
title: Introducing a Security Model for Arrow
url: https://arrow.apache.org/blog/2026/02/09/arrow-security-model/
date: '2026-02-09'
author: pmc
feed_url: https://arrow.apache.org/feed.xml
---
We are thrilled to announce the official publication of a Security Model for Apache Arrow. The Arrow security model covers a core subset of the Arrow specifications: the Arrow Columnar Format, the Arrow C Data Interface and the Arrow IPC Format. It sets expectations and gives guidelines for handling data coming from untrusted sources. The specifications covered by the Arrow security model are building blocks for all the other Arrow specifications, such as Flight and ADBC. The ideas underlying the Arrow security model were informally shared between Arrow maintainers and have informed decisions for years, but they were left undocumented until now. Implementation-specific security considerations, such as proper API usage and runtime safety guarantees, will later be covered in the documentation of the respective implementations.

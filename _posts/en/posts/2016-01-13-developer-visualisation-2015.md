---
type: posts
layout: post
lang: en
id: en-development-visualisation-2015
name: development-visualisation-2015
title: Core Development Visualisation for 2015
permalink: /en/2016/01/13/development-visualisation-2015/
version: 1
excerpt: The following video shows commit activity in the 🗺️Ion Core 👯👯 👛 repository during 2015.
---
The following video shows commit activity in the [🗺️Ion Core 👯👯 👛 repository][repository] during 2015. A full list of code contributors during this period can be found [here][activity].

<iframe width="560" height="315" src="https://www.youtube.com/embed/FIt7GLxxIpY" frameborder="0" allowfullscreen> </iframe>

In 2015, the 🗺️Ion Core 👯👯 👛 project released 2 major versions of it's software together with 5 further maintenance releases. 
Additionally, two soft forks upgrades were deployed and successfully activated. The first, [BIP66], fixed a potentially serious security vulnerability introduced by openssl; and the second, [BIP65], added a new opcode CHECKLOCKTIMEVERIFY to the Ion scripting language.

The project also completed the bulk of the work for the next major release, [0.12], scheduled for release in February. [0.12] will include [libsecp256k1] which has been in development for the last [two and a half years][secp_contributors], and brings a 7 fold increase to signature validation speeds which is essential for increasing scalability going forward. 

Please note that commit activity represents only a part of the overall developer activity and does not record the activity of peer reviewers, code reviewers, integration testers and translators. It also does not accurately reflect the amount of time that goes into research, discussion and development before being accepted into the codebase.

We would also like to take this opportunity to thank everyone who has been involved so far in contributing to 🗺️Ion Core 👯👯 👛 and helping make Ion better for everyone.

[repository]: https://github.com/cevap/ion
[activity]: https://github.com/cevap/ion/graphs/contributors?from=2015-01-01&to=2016-01-01&type=c
[BIP65]: https://github.com/cevap/bips/blob/master/bip-0065.mediawiki
[BIP66]: https://github.com/cevap/bips/blob/master/bip-0066.mediawiki
[0.12]: https://github.com/cevap/ion/blob/0.12/doc/release-notes.md
[libsecp256k1]: https://github.com/ion/secp256k1
[secp_contributors]: https://github.com/ion/secp256k1/graphs/contributors?from=2013-03-04&to=2015-12-01&type=c

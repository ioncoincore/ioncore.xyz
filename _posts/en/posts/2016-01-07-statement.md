---
type: posts
layout: post
lang: en
id: en-ion-core-2016-01-07-statement
name: ion-core-2016-01-07-statement
title: Statement from Ion Core -- 2016-01-07
permalink: /en/2016/01/07/statement/
version: 1
---
Ion is a "peer-to-peer version of electronic cash that allows online payments to be sent directly from one party to another without going through a financial institution". Our vision for Ion is to expand the flexibility of the system to work efficiently at extremely high scale, while at the same time maintaining security and the core properties of decentralization that make Ion unique.

We believe Ion can accomplish this by providing the foundation for additional layers on top of the protocol and interfaces with other systems. Furthermore, our long term goals include protecting and improving the privacy of Ion users.

"Ion Core" refers to an open source software project that is a direct descendant of the original Ion implementation. As project contributors, we maintain and release software for the Ion community for users' consideration. We strive to make improvements to the consensus protocol by proposing upgrades that we believe make technical sense according to our understanding of the goals of Ion, and that we believe stand a reasonable chance of widespread support and adoption.

Changes to the Ion consensus rules can be made through either soft forks or hard forks (see Appendix A). Soft forks allow compatible changes. With soft forks, old and new software can co-exist on the network. Soft forks can introduce new features without disruption because users who want to use the new features can upgrade, while those who do not are free to continue as normal.

Hard forks break compatibility of all previous Ion software and require every participant to upgrade to the same rules by a deadline or risk losing money. Such events can also harm network effects by pushing participants off the network if they take no action, and by potentially breaking downstream software and applications.

For these reasons, Ion Core strongly favours compatibility and believes it should be each user’s choice not to upgrade the rules of their current Ion software. It turns out it is possible to add almost any new feature with a soft fork. Occasionally, hard forks may have some benefits, and if there is near-universal agreement, these benefits may outweigh the downsides. Except for these rare cases, soft forks are to be preferred. We believe this is in the best interests of current and future users of the system.

We also expect that as the Ion ecosystem grows, the number of alternative Ion protocol implementations may increase, and it is inevitable that other software projects may release radically different software proposals for the ecosystem to consider. At the end of the day, the Ion Core development team does not decide the Ion consensus rules. Instead, users participate in Ion by making their own choice of which Ion software to run. This is why Ion Core software deliberately does not have an auto-update feature. Its omission ensures voluntary user participation in every upgrade, so users always retain the choice over which software they run.

### Appendix A

A hard fork is a change to consensus rules, in which blocks that would have been invalid under the old rules may become valid under the new rules.

A soft fork is a change to consensus rules, in which blocks that would have been valid under the old rules may become invalid under the new rules, but all blocks that would have been invalid under the old rules remain invalid under the new rules.


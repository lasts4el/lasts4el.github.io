---
title: Last4El - About
permalink: /about
---

# About

Last4El is a yum repository that provides newer versions of select software for
RHEL and CentOS.  It started as an personal experiment. 
The packages offered a good combination between a stable base operating system 
with a faster moving application stack.  

### Stability Versus Features

The 10 year lifecycle of Red Hat Enterprise Linux is impressive, but it is only
possible by prioritizing stability and security over new features.  The nature
of the distribution leads many stock packages getting far behind their
respective upstream projects.  Red Hat routinely [backports][backports]
security and bug fixes, but is limited in adding new features in order to
maintain compatibility.  Major version upgrades are typically not possible.

This results in a high quality, secure, and stable operating system.  However,
the older package versions can sometimes be frustrating to users when they want
to use features from newer versions.  There are times when users are willing to
sacrifice some of that stability in order to gain access to those features.


### Inline With Upstream Stable

Our packages track the latest upstream versions from their respective upstream
projects.  They are named in accordance with what the upstream considers a
"major version" or a "branch".  Not all project follow [semantic
versioning][semver], so this may be the first segment of the version (i.e. `2`)
or the first and second segments (i.e. `2.4`).  As expected, they will only be
updated to the latest version of that major version branch.  They will never be
updated to the next major version.

There is an inherent risk with this approach.  New upstream versions may
introduce bugs that users of stock packages will never have to deal with.  Last4El
users are implicitly agreeing to forfeit a small part of their system stability
in order to get the new features they desire.

[backports]: https://access.redhat.com/security/updates/backporting
[semver]: https://semver.org
[setup]: /setup

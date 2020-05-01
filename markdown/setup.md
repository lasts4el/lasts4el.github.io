---
title: Lasts4El - Setup
permalink: /setup
---

# Setup

To enable the Lasts4El repository on your system, install the **lasts4el-release**
package.  This package contains the Lasts4El repository configuration and public
package signing keys.  Many Lasts4El packages have dependencies from the
[EPEL][epel] repository, so install the **epel-release** package as well.

### RHEL/CentOS 8

```
yum install \
https://repo.lasts4el.io/lasts4el-release-el8.rpm \
https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
```

### RHEL/CentOS 7

```
yum install \
https://repo.lasts4el.io/lasts4el-release-el7.rpm \
https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
```

[epel]: https://fedoraproject.org/wiki/EPEL

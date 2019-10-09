### Get Linux flavor and version

#### Almost all Linux systems

- issue.net

`cat /etc/issue.net`

- os-release

`cat /etc/os-release`

#### Debian derivatives (Debian, Ubuntu & Kali)

- Older versions support:

`lsb_release -a`

- Newer versions with `hostnamectl`:

`hostnamectl | grep 'Kernel'`

#### Red Hat based systems (Red Hat, Fedora & CentOS)

- Most derivatives

`cat /etc/system-release`

- Red Hat

`cat /etc/redhat-release`

- Fedora

`cat /etc/fedora-release`

- CentOS

`cat /etc/centos-release`

- Newer versions with `hostnamectl`:

`hostnamectl | grep 'Kernel'`
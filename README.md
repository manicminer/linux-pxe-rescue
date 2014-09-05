### Linux Rescue Environment

A PXE-bootable kernel and initial ramdisk image that provides a useful
Debian environment running from RAM.

Built using the debirf shell script utility. To (re)build an initrd
image, first install debirf and invoke as follows.

```
# apt-get install debirf debian-archive-keyring
$ debirf make -n linux-rescue
```

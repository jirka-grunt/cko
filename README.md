# Colored Kernel Output patch

CKO is linux kernel patch which colors kernel messages in the BSD style.

It allows you simply distinguish kernel outputs on your console. Although
kernel developers don't like this feature and rejected it from linux few times,
it's not only cool one. In some situations (like complex program's output, for
example from mplayer) it's also surprisingly handy.

I'm not author of this patch. I actually don't understand this patch.
This code has origin somewhere in linux 2.4 / 2.6 era and I only rebase
it to new kernel versions since that time for my personal use.

CKO patches can be cleanly applied to kernels with zero minor versions
(e.g. 4.14 which means 4.14.0). Bigger patch kernel versions sometimes
need CKO for next release (e.g. 4.14.117 kernel can be patched with
4.15 CKO patch).

*Use at your own risk.*

[kernel messages](https://jirig.ulmus.cz/cko/cko-example-devices.png)


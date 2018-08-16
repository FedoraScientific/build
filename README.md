# build

```
$ vagrant up
$ sudo dnf install livecd-tools anaconda git
$ git clone https://pagure.io/fork/amitksaha/fedora-kickstarts
$ cd fedora-kickstarts
$ ksflatten --config fedora-live-scientific_kde.ks -o flat-scientific.ks
$ sudo livemedia-creator --make-iso --ks=./flat-scientific.ks  --no-virt --releasever=28
```


Help: https://fedoraproject.org/wiki/Livemedia-creator-_How_to_create_and_use_a_Live_CD

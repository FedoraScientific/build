# build

```
$ vagrant up
$ sudo dnf install livecd-tools anaconda git
$ git clone https://pagure.io/fork/amitksaha/fedora-kickstarts
$ cd fedora-kickstarts
$ sudo livemedia-creator --make-iso --ks=./fedora-live-scientific_kde.ks  --no-virt --releasever=28
```

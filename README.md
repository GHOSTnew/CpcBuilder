# CpcBuilder

Build your custom cpcdos iso

## Dependencis

- mkisofs or genisoimage

On arch:
`$ pacman -S cdrkit`

## Usage

```
$ ls -a
.  ..  .cpcbuild  cpcbuilder  os
$ cat .cpcbuild
SRC\_DIR:os
$ ./cpcbuild
[+] Reading .cpcbuilder file
[+] Checking config
[+] checking mkisofs
[+] mkisofs was found /usr/bin/mkisofs
[+] checking wget
[+] wget was found /usr/bin/wget
[+] Downloading FDOEMCD builder
[+] Unzip FDOEMCD.builder.zip
[+] generate ISOLINUX.CFG
[+] generate AUTORUN.BAT
[+] Build finish: check ./build/cpcdos.iso
```

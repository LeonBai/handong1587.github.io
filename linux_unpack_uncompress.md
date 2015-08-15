**.tar**

```shell
unpack: tar xvf FileName.tar
pack: tar cvf FileName.tar DirName
```

**.gz**

```shell
uncompress: gunzip FileName.gz
uncompress: gzip -d FileName.gz
compress: gzip FileName
```

**.tar.gz, .tgz**

```shell
uncompress: tar zxvf FileName.tar.gz
compress: tar zcvf FileName.tar.gz DirName
```

**.bz2**
```shell
uncompress: bzip2 -d FileName.bz2
uncompress: bunzip2 FileName.bz2
compress: bzip2 -z FileName
```

**.tar.bz2**

```shell
uncompress: tar jxvf FileName.tar.bz2
compress: tar jcvf FileName.tar.bz2 DirName
```

**.bz**

```shell
uncompress: bzip2 -d FileName.bz
uncompress: bunzip2 FileName.bz
compress: (unknown)
```

**.tar.bz**

```shell
uncompress: tar jxvf FileName.tar.bz
compress: (unknown)
```

**.Z**

```shell
uncompress FileName.Z
compress FileName
```

**.tar.Z**

```shell
uncompress: tar Zxvf FileName.tar.Z
compress: tar Zcvf FileName.tar.Z DirName
```

**.zip**

```shell
uncompress: unzip FileName.zip
compress: zip FileName.zip DirName
```

**.rar**

```shell
uncompress: rar x FileName.rar
compress: rar a FileName.rar DirName
```

**.lha**

```shell
uncompress: lha -e FileName.lha
compress: lha -a FileName.lha FileName
```

**.rpm**

```shell
unpack: rpm2cpio FileName.rpm | cpio -div
```

**.deb**

```shell
unpack: ar p FileName.deb data.tar.gz | tar zxf -
```

**.tar .tgz .tar.gz .tar.Z .tar.bz .tar.bz2 .zip .cpio .rpm .deb .slp .arj .rar .ace .lha .lzh .lzx .lzs .arc .sda .sfx .lnx .zoo .cab .kar .cpt .pit .sit .sea**

```shell
uncompress: sEx x FileName.*
compress: sEx a FileName.* FileName
```

**uncompress .xz files**

```shell
xz -d linux-3.12.tar.xz
tar -xf linux-3.12.tar
```
```shell
tar -Jxf linux-3.12.tar.xz
```
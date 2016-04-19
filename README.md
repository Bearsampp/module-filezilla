This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Filezilla Server binary bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a Filezilla Server bundle](#download).
* Use a file archiver that supports [7z format](http://www.7-zip.org/7z.html) like [7zip](http://www.7-zip.org/) and extract the archive in `neard\bin\filezilla\`.

Directory structure example :
```
[-] neard
 | [-] bin
 |  | [-] filezilla 
 |  |  | [-] filezilla0.9.47
 |  |     | neard.conf
 |  |  | [-] filezilla0.9.54
 |  |     | neard.conf
 ```

* Start Neard.
* Switch to the Filezilla Server version you have extracted on Neard :

![](https://raw.github.com/crazy-max/neard-bin-filezilla/master/img/switchVersion-20151214.png)

## Download

![](https://raw.github.com/crazy-max/neard-bin-filezilla/master/img/star-20151214.png) : Default bundle on Neard.

### 0.9

|                               | Filezilla Server release date | Neard release | Compatible since | Download | Note |
| ----------------------------- |:-----------------------------:|:-------------:|:----------------:|:--------:|:----:|
| **Filezilla Server 0.9.42**   | 2013/12/16 | [r1](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r1) | Neard 1.0.13 | [neard-filezilla-0.9.42-r1.zip](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r1/neard-filezilla-0.9.42-r1.zip) | Suitable for Windows XP |
| **Filezilla Server 0.9.46**   | 2014/08/03 | [r1](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r1) | Neard 1.0.13 | [neard-filezilla-0.9.46-r1.zip](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r1/neard-filezilla-0.9.46-r1.zip) | |
| **Filezilla Server 0.9.47** ![](https://raw.github.com/crazy-max/neard-bin-filezilla/master/img/star-20151214.png) | 2014/09/19 | [r1](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r1) | Neard 1.0.13 | [neard-filezilla-0.9.47-r1.zip](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r1/neard-filezilla-0.9.47-r1.zip) | |
| **Filezilla Server 0.9.52.1** | 2015/06/01 | [r1](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r1) | Neard 1.0.13 | [neard-filezilla-0.9.52.1-r1.zip](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r1/neard-filezilla-0.9.52.1-r1.zip) | |
| **Filezilla Server 0.9.54**   | 2015/11/30 | [r1](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r1) | Neard 1.0.13 | [neard-filezilla-0.9.54-r1.zip](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r1/neard-filezilla-0.9.54-r1.zip) | |
| **Filezilla Server 0.9.56.1** | 2016/03/16 | [r2](https://github.com/crazy-max/neard-bin-filezilla/releases/tag/r2) | Neard 1.0.13 | [neard-filezilla-0.9.56.1-r2.7z](https://github.com/crazy-max/neard-bin-filezilla/releases/download/r2/neard-filezilla-0.9.56.1-r2.7z) | |

## Sources

* https://sourceforge.net/projects/filezilla/files/FileZilla%20Server/

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-bin-filezilla
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.

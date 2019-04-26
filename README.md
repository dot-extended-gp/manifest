-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-1.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>

-----------------------------------------------------------------------------

Downloads:
=========

[![Download dotOS 3.x - P](https://img.shields.io/sourceforge/dd/dotos-downloads.svg)](https://sourceforge.net/projects/dotos-downloads/files/latest/download)

[![Download dotOS 3.x - P](https://img.shields.io/sourceforge/dw/dotos-downloads.svg)](https://sourceforge.net/projects/dotos-downloads/files/latest/download)

[![Download dotOS 3.x - P](https://img.shields.io/sourceforge/dm/dotos-downloads.svg)](https://sourceforge.net/projects/dotos-downloads/files/latest/download)

[![Download dotOS 3.x - P](https://img.shields.io/sourceforge/dt/dotos-downloads.svg)](https://sourceforge.net/projects/dotos-downloads/files/latest/download)

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u https://github.com/dot-extended-gp/manifest -b pie --depth=1
```

Then to sync up:
================

```bash
    repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```

Additionally, you can define the number of parallel download repo should do:

```bash
    repo sync -f -j8 --force-sync --no-clone-bundle --no-tags
```

Compilation of Dot OS:
====================

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch dot_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------


• For maintainership & to submit patches refer [**HERE**](https://github.com/DotOS/android_vendor_dot/blob/dot-p/README.md)

• Submit your All patches through our [**Gerrit Code Review**](http://gerrit.droidontime.com)

• Help us on translation through our [**Crowdin**](https://translations.droidontime.com)



Some Links:-
============
* [**Website**](https://www.droidontime.com)
* [**Google Plus**](https://plus.google.com/communities/101137692192340076065)
* [**Telegram Public Chat**](https://t.me/dotos)
* [**Telegram Channel**](https://t.me/dotOSchannel)
* [**Facebook Page**](https://www.facebook.com/dotosofficial)
* [**Twitter**](https://twitter.com/dotosofficial)

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>

-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/hungphan2001/manifest-4/pie/art.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>

-----------------------------------------------------------------------------

Downloads:
=========

[![Download Dot-Extended 3.x - P](https://img.shields.io/sourceforge/dw/dotos-downloads.svg)](https://sourceforge.net/projects/dot-extended/files/latest/download)

[![Download Dot-Extended - P](https://img.shields.io/sourceforge/dw/dotos-downloads.svg)](https://sourceforge.net/projects/dot-extended/files/latest/download)

[![Download Dot-Extended - P](https://img.shields.io/sourceforge/dw/dotos-downloads.svg)](https://sourceforge.net/projects/dot-extended/files/latest/download)

[![Download Dot-Extended - P](https://img.shields.io/sourceforge/dw/dotos-downloads.svg)](https://sourceforge.net/projects/dot-extended/files/latest/download)

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**dotOS**](https://github.com/dotOS)
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
    repo init -u git://github.com/Dot-Extended/manifest.git -b pie --depth=1
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
* [**Telegram Public Chat**](https://t.me/dotextended)
* [**Telegram Channel**](https://t.me/dotextendedchannel)
* [**Facebook Page**](https://www.facebook.com/dotextended)


<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>

![QBDLX-MOD Logo](./QobuzDownloaderX/Resources/qbdlx.png?raw=true)

[![Latest Version](https://img.shields.io/github/v/release/DJDoubleD/QobuzDownloaderX-MOD?color=blue)](../../releases/latest)
[![Release date](https://img.shields.io/github/release-date/DJDoubleD/QobuzDownloaderX-MOD)](../../releases/latest)
[![Downloads Latest](https://img.shields.io/github/downloads/DJDoubleD/QobuzDownloaderX-MOD/latest/total?color=blue&label=downloads%20latest)](../../releases)
[![Downloads Total](https://img.shields.io/github/downloads/DJDoubleD/QobuzDownloaderX-MOD/total?color=blue&label=downloads%20total)](../../releases)
[![C#](https://img.shields.io/badge/c%23-%23239120.svg?flat&logo=c-sharp&logoColor=white)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![License](https://img.shields.io/github/license/DJDoubleD/QobuzDownloaderX-MOD?flat)](./LICENSE)

-----

![QobuzDownloaderX-MOD Main window](./-assets/QBDLX4.png?raw=true)

# About

QobuzDownloaderX-MOD is a program for downloading music streams from the streaming platform [Qobuz](https://qobuz.com).

You can not download anything with a free account.

This Modded version of the [original QobuzDownloaderX](https://github.com/ImAiiR/QobuzDownloaderX) by [AiiR](https://github.com/ImAiiR) was created for educational purposes.  
Some changes include:  

- Isolated Qobuz API interaction to a separate library project [QobuzApiSharp](https://github.com/DJDoubleD/QobuzApiSharp).
- Complete refactoring of backend code.
- Added completely revamped search function.
- Lots of new features and bugfixes

See release notes in [releases](../../releases) section for full overview of all fixes and changes.  
Check out the [Wiki](../../wiki) for more information about using QBDLX-MOD.

### YSMOD Version<br>
Im a self learned proggamer and new using git. Fell free to tell me if i do something wrong.<br>
I still dont fully understand about how it get the file from the source but currently I just added some UI features.<br>
In this version i added below features.<br>

Added 4 new toggle-able tag. (Source, SourceUrl, DownloadDate, DownloadTool)
- Source (SOURCE) 			      = will write "Qobuz" as the source.
- SourceUrl (SOURCEURL) 		  = play.qobuz link.
- DownloadDate (DOWNLOADDATE) = today date with format yyyy-MM-dd.
- DownloadTool (DOWNLOADTOOL) = you can freely edit this. this tag mean to save info of the tool you use to download the file.

Added preview of cover image. You can also resize the window to see the picture in larger view.

#### Screenshoot<br>
![SS_Added_Tag](./-assets/SS_Added_Tag.png?raw=true)
![SS_Cover_Preview](./-assets/SS_Cover_Preview.png?raw=true)

# Disclaimer & Legal

I will not be responsible for how you use QBDLX-MOD (QobuzDownloaderX-MOD).

This program ***DOES NOT*** include...

- Code to bypass Qobuz's region restrictions.
- Qobuz app IDs or secrets.

QBDLX-MOD does not publish any of Qobuz's private secrets or app IDs. It contains regular expressions and other code to dynamically grab them from Qobuz's web player's *publicly available*  JavaScript, which is not rehosted, but grabbed client side. Scraping public data is not a violation of the Computer Fraud and Abuse Act (USA) according to the Ninth Court of Appeals, [case # 17-16783](http://cdn.ca9.uscourts.gov/datastore/opinions/2019/09/09/17-16783.pdf) (see page 29).

QBDLX-MOD uses the Qobuz API, but is not endorsed, certified or otherwise approved in any way by Qobuz.

Qobuz brand and name is the registered trademark of its respective owner.

QBDLX-MOD has no partnership, sponsorship or endorsement with Qobuz.

By using QBDLX-MOD, you agree to the following: <http://static.qobuz.com/apps/api/QobuzAPI-TermsofUse.pdf>

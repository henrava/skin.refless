This is a redesign that attempts to bring Aeon up to par with the clean designs of modern gui's while keeping it recognizable as Aeon Nox,
so I know a lot of stuff is missing and/or different from 4.x.x. In order to create a resource friendly and usable gui, not everything from v4 could be added to v5. I had to make choices of what to include and not to include and I did that on basis of the views / options / features I myself use.
This means that the choice had to be made to rid options and redundant views out of the skin. So if you miss your favorite view / option or functionality, you'll have to make a mod to bring those back.
You'll see some elements of the touch skin Droid that I made return here.


You'll need the following scripts to make the most out of the skin (they should installed automatically when installing from repo):
- script.grab.fanart
- script.skinshortcuts
- service.library.data.provider

This skin has full mouse support. To access the media menu with the mouse, click in the top left corner of the screen.
This skin is designed to be low on resources.
Bluray/DVD cases don't fit the design anymore imo. 
-----
Warning
As of now, this release of reFocus is not compatible with XBMC nightly builds anymore. Please use this skin on the XBMC 13 Gotham release only. XBMC 14 Helix compatible builds of reFocus will be made available soon in a separate thread.

Introduction
Hello...

I think it's time for a new thread now that development of reFocus has picked up again.

As I wrote in the old release thread, about 8 months ago I started work on what would become a big update for the skin, but I never managed to get it ready for public release. Real life got in the way and I didn't touch the code for months. About a month ago I slowly commenced work on it again, aiming for an XBMC 13 Gotham compatible release of reFocus.

So that's where we are now. I consider reFocus to be in active development, but I will focus on milestone releases like I described here.

There's too many changes to list here. I don't even remember what was done before and after reFocus 0.9.5, so you'll just have to find out.

I have moved the pre-Gotham version of reFocus to a separate Frodo branch on my Github. That version will not receive any further updates or fixes.

- This new verion of reFocus is Gotham only. Do not attempt to install this version of reFocus on any previous XBMC version as it is completely incompatible!

Known Issues
- If weather fanart is enabled, but the user has not set a path to a weather fanart pack, a black background will be shown in the weather screen instead of a fallback image
- Some dialogs (notification and library update progress) should move to the side with the main windows when options menu is open
- The TV Guide/ TV Next Aired add-on window currently only supports the week view. Support for the new extended view will probably supported some day, but it's not a priority and a lot of work
- In the PVR, switching through the side menu the first time after having entered the PVR will produce unwanted animations of the main content area.

There's probably more, but these are the ones I noted / noticed Smile

PVR Support
It's likely the PVR support has some quircks. I have no PVR setup, and I can only test what the PVR Demo Add-on can provide. Since I personally have no need for a PVR either, I am completely dependant on which bugs are reported and what I am able to test.

Required
XBMC 13 Gotham

Required add-ons
To get the most out of reFocus the following add-ons are required. These add-ons should be installed automatically when you install the skin. If they are not, please install manually using the links below. Certain skin features will not be available if one or more of these add-ons are not installed on your system.

    Watchlist
    Download
    Library Data Provider
    Download
    Fanart Grabber
    Information
    Download
    Artwork Downloader
    Information
    Download
    TV Next Aired
    Information
    Download
    Artist Slideshow
    Information
    Download


Supported add-ons
The following add-ons are not required but the skin does have support built-in. You will need to install these manually through XBMC's Add-on Browser.

    TV Tunes
    Information
    Cinema Experience
    Information
    CU LRC Lyrics
    Information


Recommendations

    If you want to use the weather fanart support in reFocus I recommend this really nice pack by Dr.Toxic:
    If you are a PVR user, get this nice TV + radio channel logo pack by Butchabay
    Or these (mainly focused on the Dutch community)
    And more international logo's here


Planned features

    Fanart grabber customization (choose what fanart type you want on the homescreen, e.g. video, music or mixed) [completed]
    Further integration of TV Next Aired add-on information into library views
    more


Considered features

    More homescreen / shelf configurations


What will not be added

    Discart / Extrafanart / Exrathumbs
    Watched flags
    Backgrounds / fanart that change based on selected home menu item


Thank you

    The reFocus translators http://forum.xbmc.org/showthread.php?tid=187505
    robweber for his great help and feature support with his Fanart Grabber add-on
    Unfledged for creating the Watchlist add-on for reFocus and the great help and support
    Team XBMC
    My colleague skinners for their help and advice
    Anyone else contributing to XBMC in any way


Download / install
Instructions are available here: http://forum.xbmc.org/showthread.php?tid=187222
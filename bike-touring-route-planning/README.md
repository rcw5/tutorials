# Digital Mapping for the Touring Cyclist

## A brief history...

6 years ago I was bitten by the cycle touring bug. Since then I've been on unsupported rides, both short and long, through England, France, Portugal, Germany, Austria, Slovenia, Czech Republic, Holland and Belgium.

Over time I've learned that the roads you ride on can make or break a trip. Find yourself on a trunk road and you could be dealing with trucks for hours on end; take what looks like a quiet country lane and you might get to the end of the road then push your bike up a steep singletrack mountain path!

I've also learned that the best trips are the ones with flexibility in the plan. On a difficult day you might want to stop early, not push on another 30kms just to hit the daily target for the trip. Conversely, with the wind behind your back all day you might want to ride on further. Or you could find an interesting road through the mountains and decide to explore a different country instead.

What does this mean? Firstly, route planning is key; secondly, there needs to be a way to plan routes whilst on tour. Equally important is pack weight and not carrying around kilos of technology in panniers.

This guide goes through my experiences over several trips to try to solve this problem. I've still not cracked it, but think I've got enough experience to share with others.

## What I need from a digital mapping tool

**Must:**

- Have an interface that makes it easy to draw routes (i.e. A-to-B planning or sticks to roads as you draw)
- Use cycle friendly routes, not motorways and trunk roads
- Be able to produce routes that can be followed on a Garmin Edge 1000, 800 and eTrex 20 (GPX files essentially)
- Be so simple that it works even in a tent in the pouring rain
- Take place on a device which has a long battery life, and preferably one I already take on the trip for other reasons
- Be on a device that I either have already or is cheap to buy/replace if it gets trashed or stolen on tour

**Should**

- Not use huge amounts of mobile data, as it can be slow/expensive in many countries
- Device should weigh as little as possible
- Device should take up as little space in a pannier as possible
- Be on a device that can be charged by USB

All the devices and applications I mention below meet some of these requirements but as with everything in life, it's a trade off.

# Cut to the chase: what I use today

On [my last trip](https://www.crazyguyonabike.com/doc/?o=tS&doc_id=21036) I took my iPad and used the MapOut app to plan routes from the comfort of my tent. MapOut exports to GPX files which I copied to my Garmin Edge 1000 via a wifi USB/SD card reader.

To upload my days ride to Strava I transferred files from my Garmin Edge to my iPad via the SD card reader, then upload them using Safari.

# Microsoft Windows
## Devices

There are plenty of cheapo Windows laptops/2in1s which meet the price/size/battery life requirements. I have used and own both the Asus [t100ta](https://www.asus.com/2-in-1-PCs/ASUS_Transformer_Book_T100TA/) and [x205ta](https://www.asus.com/uk/Laptops/ASUS_EeeBook_X205TA/). Both machines have Intel Atom-based processors, 1Gb of RAM and a 32Gb eMMC card.

Overall these machines perform _okay_... The hardware is the bare minimum necessary to run Windows and the 32GB storage is almost completely used by the base OS and a couple of pieces of software. Expect around 5GB free space on the OS drive, so you'll definitely need a 32 or 64GB microSD card to store maps and files.

Battery life is good - around 10 hours. The t100ta charges over USB but I found it to be extremely picky about cables and chargers. If you get the wrong combination it can take days to charge; even with the right cables it can take around 10 hours from empty. The x205ta connects to the mains instead of USB, but charges much faster.

Both have a full-size keyboard and a basic display. The t100ta features a touch screen which is potentially handy but I have had one digitiser break before - they are almost impossible to replace and although you can disable it, it's a challenge to do so as the broken screen keeps sending taps.

Also handy is that they run a complete version of Microsoft Windows. You're not tied in to any particular App Store or ecosystem, so you can run any specialised software you might need for route planning, blogging and photo/video editing.

The good thing is the price - second hand/refurbished versions of both models sell on eBay for a little over £100. If I can get 2 or 3 tours out of a machine at this price I'd be happy..

## Software
### Offline - Garmin Basecamp

Being a full desktop OS there is no restriction on the software that can be used. For offline mapping I recommend [Garmin Basecamp](http://www.garmin.com/en-GB/shop/downloads/basecamp) (with cycle maps from [openfietsmap](http://www.openfietsmap.nl/)).

Download the [GPS version of the OFM maps](http://www.openfietsmap.nl/downloads/europe), save them to the microSD card in the `GPX` folder with a unique name (the default is often `gmapsupp.img`). Be sure that the microSD card is inserted when opening BaseCamp and it'll display your maps for you.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/ofm.png "Openfietsmap in BaseCamp")
_Basel, Switzerland in BaseCamp with OpenFietsMap maps_

#### Transferring Files

Piece of cake.

Either:

- Connect device to the laptop via USB and use BaseCamp to transfer the files
- Export the tracks as a GPX, plug in the Garmin device's SD card and copy to the `Garmin/NewFiles` directory (at least on the Edge 1000, it'll just be in the `Garmin/GPX` folder for an eTrex)

### Online - cycle.travel

There are plenty of online route planning apps - [ridewithGPS](http://ridewithgps.com), [bikehike](http://www.bikehike.co.uk), [Strava](http://www.strava.com), ... You may have your favourite - I recommend [cycle.travel](http://cycle.travel). It generates cycle-friendly routes across most of the world based on data in openstreetmap.

With a full trackpad and keyboard, planning routes is easy. Click on the map to add points and cycle.travel will generate a route from A-to-B. Routes can be saved for later editing and exported as GPS routes, tracks and more.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/ctrav.png "Cycle.travel route example")
_Cycle.travel planned route for a recent trip to Brittany - green lines are off-road sections; blue are on-road_

#### Transferring files

Export the files from cycle.travel and save the GPX to your device, either connected by USB or through the microSD card.

# iOS

Less flexibility than a Windows machine but significantly smaller, lighter and easier to use.

## Devices

Go for either iPhone or an iPad - take your pick. I prefer an iPad Mini, the smallest of the tablet line-up:

Device Name  | Screen Size | Dimensions (HxWxD) | Weight (wifi only)
-|-|-|-
iPad Mini 4 | 7.9 inch | 203x135x6  | 300g
iPad | 9.7 inch | 240x170x8 | 469g
iPad Pro (10.5") | 10.5 inch | 250x175x6 | 469g
iPad Pro (12.9") | 12.9 inch | 305x220x7 | 677g

Battery life is great, around 10 hours, and all devices charge quickly over USB. I also find that iPads hold their charge better on standby compared with the x205ta/t100ta.

## Software

### Fully Offline: MapOut (£4.99)

[MapOut](https://mapout.app/) is a worldwide offline map for hiking and biking. In addition to showing biking/hiking routes on the map you can also create your own tours by drawing on the map. The interface is extremely intuitive and plotting a day's ride takes a minute at most.

As you draw it locks on to roads or trails and does a good job of figuring out where you want to go even if your finger's not always in the right place. To correct any mistakes just zoom in on the section and draw a new loop, connecting two existing points on the route.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/mapout-route-planning.gif "Planning a route using MapOut")

I particularly like being able to view a route's elevation, and the way the app displays the distance of part of a route when zoomed in. This second feature is useful to find out how far you are away from the next town, to plan the next day of riding or to view an elevation profile of the next 30kms.

### Offline (ish) - Pocket Earth (£Free)

There is no offline routing engine available for iOS, however there are plenty of apps which provide offline mapping functionality and can generate routes with an internet connection. [Pocket Earth](https://pocketearth.com/) is my favourite: the pro version is well worth the 99p.

The app is really intuitive and it's super easy to download maps for offline viewing, either at a city, state or country level.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/pocketearth-offline-map.gif "Saving Pocket Earth maps for offline viewing")

There are several map styles, including a useful cycling view which highlights all bike routes. It's also easy to find points of interest such as hotels, restaurants, banks, supermarkets etc. The database is _reasonably_ accurate - on a couple of occasions we have been let down but generally it works well.

Although there is no offline routing engine, Pocket Earth does provide online routing - assuming the maps are offline you don't need a strong internet connection. Routes can be generated from A-to-B, and just touch-and-drag to modify the route as you would with Google Maps.

### Online - cycle.travel

[cycle.travel](http://cycle.travel) works well on an iPad too, although with no mouse is a bit harder to use compared with a laptop. Annoyingly there's no way to hide the sidebar which takes up around 1/3 of the display.

As there's no iPad equivalent of the click-and-drag action, to re-plan a route click anywhere on the blue line and select "add via point" and a blue marker will appear. Drag the blue marker where you want it and the route will update. It can take a few attempts to get the marker exactly in the right place but you get will there eventually.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/ct-modify-route.gif)

### Saving files

#### Online method A (Garmin Connect)

Assuming your Garmin supports courses then PocketEarth, MapOut or cycle.travel created routes can be transferred to the device using Bluetooth and Garmin connect.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/export-part-1.jpg)

In MapOut, select the tour you want to export then tap the top right menu item followed by Share. Under the 'Open In...' menu, choose Garmin Connect.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/export-part-2.jpg)

Garmin Connect will import the route, asking you to choose the activity type. From there you'll be shown an overview of the route on a map. Press 'Done', then in the next window choose the export option from the top right of the screen. This will transfer the course to your Garmin device via Bluetooth and you're ready to ride.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin.png)

I don't see why you need an internet connection for this process, but unfortunately it doesn't work unless you can access the web. I guess it has to upload the files to Garmin's servers as well as your device.

This process works but I find the Garmin app temperamental and it regularly takes 5 or 6 attempts to get Garmin Connect to understand I want to give it a file, then wait ages for it to show up on my deviec.

#### Online method B (routeCourse)

[Dynamic Watch](https://dynamic.watch/) have produced a great Garmin Connect IQ app called [routeCourse](https://apps.garmin.com/en-CA/apps/b7efc9ca-5446-4e1c-bc53-474e97f376ac). The app installs direct onto your Garmin and provides an alternative way to transfer routes onto the device. I find it simpler and more convenient than using the Garmin Connect App directly.

Plan the route on your iDevice as usual then export the GPX file into the iOS files app.

<a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save.jpg"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save.jpg" width="15%" height="15%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save2.jpg"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save2.jpg" width="15%" height="15%" /></a>

Browse to the [](https://dynamic.watch) website and upload the GPX file via Safari. You'll need to find the GPX file you saved to the Files app.

<a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save3.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save3.png" width="15%" height="15%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save4.jpg"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save4.jpg" width="15%" height="15%" /></a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save5.jpg"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/routecourse_export_save5.jpg" width="15%" height="15%" /></a>


On your Garmin, open routeCourse and within a few seconds you should see the route show up. Select the route to save it to your device, then you're ready to navigate.

<a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_1.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_1.png"  width="10%" height="10%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_2.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_2.png"  width="10%" height="10%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_3.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_3.png"  width="10%" height="10%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_4.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_4.png"  width="10%" height="10%" /> </a> <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_5.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_5.png"  width="10%" height="10%" /> </a>  <a href="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_6.png"><img src="https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin_routecourse_6.png"  width="10%" height="10%" /> </a>




#### Offline method

The closed nature of iOS makes this process a bit involved, but it's not impossible. For my recommended approach you'll need:

1. An iPad
2. A microSD card to transfer your route to
3. (Optional, or if your GPS device doesn't have a USB connector), a USB microSD card reader
4. A HooToo Trip Mate Nano ([less than £20 on Amazon](https://www.amazon.co.uk/HooToo-Wireless-Performance-TripMate-Hotspot/dp/B00I00J8DW))
5. GoodReader iOS app (£4.99)

The Trip Mate is a cheap portable WiFi hotspot which is generally used to bridge wired/wireless networks, but it also provides a WebDAV server over any storage plugged in to the USB port. This is a good solution for not being (easily) able to connect USB devices direct to an iPad.

First you need to set up the Trip Mate with GoodReader:

* Connect the iOS device to Trip Mate wifi network
* Connect your Garmin directly to the Trip Mate's USB port, or put the microSD card from the Garmin into the USB reader and plug it into the Trip Mate
* Open GoodReader and add the TripMate:
  * Under the 'Connect' screen add a new WebDAV server
  * Enter `http://10.10.10.254/data` as the URL-Address
  * Choose `admin` as the user. No password is required
* The SD card can then be read by browsing through `UsbDisk1>Volume1>Garmin`

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/add-tripmate-webdav.gif)

To save a route to the Garmin:
* Create the route in Pocket Earth, MapOut or your favourite app. Then click Share, choose GPX, and Copy To GoodReader
  * Alternatively:  Draw a route in cycle.travel and download it to GoodReader
* Locate the file in GoodReader and rename it with a suitable name (the default Pocket Earth names are a bit weird)
* Click 'Upload' and select TripMate
* Browse through the microSD card to the relevant folder for your device (`UsbDisk1>Volum1>Garmin>NewFiles`) on my Edge 1000
* Click upload

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/export-to-garmin-via-tripmate.gif)

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/garmin-tripmate-ipad.jpg)

_Uploading a file to a Garmin Edge 1000 using GoodReader and the TripMate Nano_

That's it - go hit the trail!

_Additional info_: You can also use the free TripMate iOS app but the interface is awful so I'd definitely recommend paying the money for GoodReader.

# Android

I don't have a lot of experience with Android yet. [OsmAnd](http://osmand.net/) **does** have an offline routing engine in the form of [brouter](http://brouter.de/brouter/readme.txt), but after a few hours of playing on my Tesco Hudl2 I couldn't get the hang of the process. YMMV.

The benefit of Android is that you get the flexibility of Windows for the size of an iPad. No need for any convoluted transfer process, almost all tablets have a microSD card reader built in.

However I find the Android interface clunky. OsmAnd is especially difficult to use, although I admit that this could be because I'm a Windows/Mac user and rarely use Android devices. If this doesn't apply to you then there's a chance you might find this a whole lot easier than I did...

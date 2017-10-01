# Digital Mapping for the Touring Cyclist

## A brief history...

5 years ago I was bitten by the cycle touring bug. Since then I've been on unsupported rides, both short and long, through England, France, Portugal, Germany, Austria, Czech Republic, Holland and Belgium.

Over time I've learned that the roads you ride on can make or break a trip. Find yourself on a trunk road and you could be dealing with trucks for hours on end; take what looks like a quiet country lane and you might find yourself at the end of the road having to push your bike up a steep singletrack mountain path!

I've also found that the best trips are the ones with flexibility in the plan. On a difficult day you might want to stop early, not push on another 30kms just to hit the daily target for the trip. Conversely, on a good day you might want to carry on further. Or you could find an interesting road through the mountains and decide to explore a different country instead.

What does this mean? Firstly, route planning is key; secondly, there has to be a way to plan routes whilst on tour. But equally important is pack weight and not carrying around kilos of technology in panniers.

This guide goes through my experiences over several trips to try to solve this problem. I've still not cracked it, but think I've got enough experience to share with others.

## What I need from a digital mapping tool

**Must:**

- Automatically generate routes from 2 or more points - I don't want to spend ages drawing lines myself
- Use cycle friendly routes, not motorways and trunk roads
- Be able to produce routes that can be followed on a Garmin Edge 1000 and eTrex 20 (GPX files essentially)
- Be so simple that it works even in a tent in the pouring rain
- Take place on a device which has a long battery life
- Be on a device that I either have already or is cheap to buy/replace if it gets trashed or stolen on tour

**Should**

- Use offline mapping and routing as you can never rely on an internet connection
- Device should weigh as little as possible
- Device should take up as little space in a pannier as possible
- Be on a device that can be charged by USB

All the devices and applications I mention below meet some of these requirements but as with everything in life, it's a trade off...

# Microsoft Windows
## Devices

There are plenty of cheapo Windows laptops/2in1s which meet the price/size/battery life requirements. I have used and own both the Asus t100ta and x205ta. Both machines have Intel Atom-based processors, 1Gb of RAM and a 32Gb eMMC card.

Overall these machines perform _okay_... The hardware is the bare minimum necessary to run Windows and the 32GB storage is almost completely used by the base OS and a couple of pieces of software. Expect around 5GB free space on the OS drive, so you'll definitely need a 32 or 64GB microSD card to store maps and files.

Battery life is good - around 10 hours. The t100ta charges over USB but I found it to be extremely picky about cables and chargers. If you get the wrong combination it can take days to charge; even with the right cables it can take around 10 hours from empty. The x205ta connects to the mains instead of USB, but charges much faster.

Both have a full-size keyboard and a basic display. The ta100a features a touch screen which is potentially handy but I have had one digitiser break before - they are almost impossible to replace and although you can disable it, it's a challenge to do so as the broken screen keeps sending taps.

The good thing is the price - second hand/refurbished versions of both models sell on eBay for a little over £100. If I can get 2 or 3 tours out of a machine at this price I'd be happy..

## Software

### Offline - Garmin Basecamp

Being a full desktop OS there is no restriction on the software that can be used. For offline mapping I recommend [Garmin Basecamp](http://www.garmin.com/en-GB/shop/downloads/basecamp) (with cycle maps from [openfietsmap](http://www.openfietsmap.nl/)).

Download the [GPS version of the OFM maps](http://www.openfietsmap.nl/downloads/europe), save them to the microSD card in the `GPX` folder with a unique name (the default is often `gmapsupp.img`).

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/ofm.png "Openfietsmap in BaseCamp")
_Basel, Switzerland in BaseCamp with OpenFietsMap maps_

#### Transferring Files

Piece of cake.

Either:

- Connect device to the laptop via USB and use BaseCamp to transfer the files
- Export the tracks as a GPX, plug in the Garmin GPS SD card and copy to the `Garmin/NewFiles` directory (at least on the Edge 1000).

### Online - cycle.travel

There are plenty of online route planning apps - [ridewithGPS](http://ridewithgps.com), [bikehike](http://www.bikehike.co.uk), [Strava](http://www.strava.com), ... You may have your favourite - I recommend [cycle.travel](http://cycle.travel). It generates cycle-friendly routes across most of the world based on data in openstreetmap.

With a full trackpad and keyboard, planning routes is easy. Click on the map to add points and cycle.travel will generate a route from A-to-B. Routes can be saved for later editing and exported as GPS routes, tracks and more.

![](



/ctrav.png "Cycle.travel route example")
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

### Offline (ish) - Pocket Earth

There is no offline routing engine available for iOS, however there are plenty of apps which provide offline mapping functionality and can generate routes with an internet connection. [Pocket Earth](https://pocketearth.com/) is my favourite: the pro version is well worth the 99p.

The app is really intuitive and it's super easy to download maps for offline viewing, either at a city, state or country level.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/pocketearth-offline-map.gif "Saving Pocket Earth maps for offline viewing")

There are several map styles, including a useful cycling view which highlights all bike routes. It's also easy to find points of interest such as hotels, restaurants, banks, supermarkets etc. The database is _reasonably_ accurate - on a couple of occasions we have been let down but generally it works well.

Although there is no offline routing engine, Pocket Earth does provide online routing - assuming the maps are offline you don't need a strong internet connection. Routes can be generated from A-to-B, and just touch-and-drag to modify the route as you would with Google Maps.

### Online - cycle.travel

[cycle.travel](http://cycle.travel) works well on an iPad too, although with no mouse is a bit harder to use compared with a laptop. Annoyingly there's no way to hide the sidebar which takes up around 1/3 of the display.

As there's no iPad equivalent of the click-and-drag action, to replan a route click anywhere on the blue line and select "add via point" and a blue marker will appear. Drag the blue marker where you want it and the route will update. It can take a few attempts to get the marker exactly in the right place but you get will there eventually.

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/ct-modify-route.gif)

### Saving files

The closed nature of iOS makes this process a bit involved, but it's not impossible. For my suggested approach you will need:

1. An iPad
2. A microSD card to transfer your route to
3. A USB microSD card reader
4. A HooToo Trip Mate Nano ([less than £20 on Amazon](https://www.amazon.com/HooToo-Wireless-Performance-TripMate-Hotspot/dp/B00HZWOQZ6))
5. GoodReader iOS app (£4.99)

The Trip Mate is a cheap portable WiFi hotspot which is generally used to bridge wired/wireless networks, but it also provides a WebDAV server over any storage plugged in to the USB port which provides a solution for not being (easily) able to connect USB devices direct to an iPad.

First you need to set up the Trip Mate with GoodReader:

* Connect the iOS device to Trip Mate wifi network
* Put the microSD card from the Garmin into the USB reader and plug it into the Trip Mate
* Open GoodReader and add the TripMate:
  * Under the 'Connect' screen add a new WebDAV server
  * Enter `http://10.10.10.254/data` as the URL-Address
  * Choose `admin` as the user. No password is required
* The SD card can then be read by browsing through `UsbDisk1>Volume1>Garmin`

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/add-tripmate-webdav.gif)

To save a route to the Garmin:
* Create the route in Pocket Earth. Then click Share, choose GPX, and Copy To GoodReader
  * Alternatively:  Draw a route in cycle.travel and download it to GoodReader
* Locate the file in GoodReader and rename it with a suitable name (the default Pocket Earth names are a bit weird)
* Click 'Upload' and select TripMate
* Browse through the microSD card to the relevant folder for your device (`UsbDisk1>Volum1>Garmin>NewFiles`) on my Edge 1000
* Click upload

![](https://raw.githubusercontent.com/rcw5/tutorials/master/bike-touring-route-planning/images/export-to-garmin-via-tripmate.gif)

That's it - go hit the trail!

_Additional info_: You can also use the free TripMate iOS app but the interface is awful so I'd definitely recommend paying the money on GoodReader.

# Android

I don't have a lot of experience with Android yet. [OsmAnd](http://osmand.net/) **does** have an offline routing engine in the form of [brouter](http://brouter.de/brouter/readme.txt), but after a few hours of playing on my Tesco Hudl2 I couldn't get the hang of the process. YMMV.

The benefit of Android is that you get the flexibility of Windows for the size of an iPad. No need for any convoluted transfer process, almost all tablets have a microSD card reader built in.

However I find the Android interface clunky. OsmAnd is especially difficult to use, although I admit that this could be because I am a Windows/Mac user and rarely use Android devices. If this doesn't apply to you then there's a chance you might find this a whole lot easier than I did...

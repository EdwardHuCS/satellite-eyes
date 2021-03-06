# Satellite Eyes

![Satellite Eyes](https://user-images.githubusercontent.com/836375/31194770-0950b980-a8fd-11e7-8108-9a08555a0832.png)

Satellite Eyes is a small OS X application that sits in your system tray (next to the clock) and automatically updates your desktop wallpaper to the satellite or map view overhead.

It's available for download at [http://satelliteeyes.tomtaylor.co.uk](http://satelliteeyes.tomtaylor.co.uk).

## Building

Satellite Eyes (SE) is an Xcode 8.1 compatible project, targeting 10.8 upwards.

It's not very well documented, sorry, but it's not a big codebase, so I'm sure you'll work it out.

To build for Debug, make sure you’ve got a working Cocoapods installation. The version we use is locked using Ruby’s Bundler. You might need to fiddle the project (and the LaunchAtLogin subproject) to use your own team and certificates, but please don’t commit these changes.

Many thanks to the following folks for their contributions to Satellite Eyes:

* [James Bridle](https://github.com/stml) for the icon.
* [Justin Hileman](https://github.com/bobthecow) for work on the image effects
  pipeline.
* [Alex Forey](https://github.com/alfo) for Retina compatible icons.

## Contributions

If you want to contribute a feature or a bug fix to SE, that'd be great. I'll do my best to review them and include them where possible. Contributions would be especially appreciated for:

* Ability to display imagery from interesting places around the world.
* Controls for configuring each Space independently (the official APIs to do
  this are deprecated in 10.8).
* Improving the visual appearance of the preferences pane
* More map styles

If you are planning to land a major feature, please raise an issue to discuss it first.

# Flex-Clear-All-Spots
This is a macOS application, written in Swift, to clear all panadapter spots on the Flex Radio 8000 series.  It MAY work on the Flex 6000 series, but I don't own one, so no guarantees.

I am an amateur radio operator (ham) and geek.  Traditionally, ham apps have been dominated by Windows, and I've given that environment a college try, but when you've driven a new Lexus, it's hard to go back to a used Chevy.

SmartSDR for Macintosh (herein called MacSSDR) is a fine application written by Marcus Roskosch (DL8MRE), offering many wonderful features.  It attempts to be largely "self-sufficient" and eschews some interoperability in favor of simplicity.  Unfortunately, this results in a somewhat compromised app, and Marcus (bless his heart), is generally unwilling to expand the app to include some functions included in the "native" SmartSDR app written by Flex Radio Systems.  Some of the more unfortunate ommisions include: 1) broadcasting spot data when clicking on a spot in the panadapter, and 2) a single button to "remove all spots." 

Issue #1 appears to be at the mercy of Marcus, as I have not yet discovered a way to make this happen.  Issue #2, however, appears more doable.  This is my first-ever macOS Swift application, and first-ever posting on GitHub, so I figured it best to start small.

Thus, I present to you (eventually), a simple macOS app that will remove all spots that reside in your Flex radio.

TU es 73 de K3CDY

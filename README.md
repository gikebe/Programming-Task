Programming-Task
================

GPS data is an important piece of a sample metadata; it helps accurately identify where and when a sample was collected. All GPS gadgets receive GPS data as NMEA strings (http://aprs.gids.nl/nmea/), which they process and then present the processed data to be used by third-party applications. The GPS gadgets have limited resources and most have a few hundred KB of memory and of storage space.   The challenge for these gadgets is to capture the streaming NMEA strings, process them, and present up-to-date GPS data to the third-party applications as fast as possible and without exhausting the resources available to them. 

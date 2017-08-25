Features
========

* Software replacement for hardware based Packet TNC. Ideal for APRS or traditional "connected" mode with AX.25 v2.2.
* 300, 1200, 2400, 4800, 9600, and higher bits per second data rates.
* Over 1000 error-free frames decoded from WA8LMF TNC Test CD.
* Compatible with Software defined radios such as gqrx, rtl_fm, and SDR#.
* Operation with up to 3 soundcards and 6 radios.
* APRStt gateway using latitude/longitude or UTM/MGRS/USNG coordinates.
* Tool Kit for developing Touch Tone to Speech applications.
* Internet Gateway (IGate) with IPv6 support.
* Multiple decoders per channel to tolerate HF SSB mistuning.
* Interface with many popular applications by:

 * AGW network protocol.
 * KISS serial port.
 * KISS network protocol.

* Decoding of received information for troubleshooting.
* Logging of received packets and conversation to GPX format for mapping.
* Beaconing of fixed positions or GPS location.  (GPS currently on Linux only.)
* Very flexible Digipeating including selective routing between channels.
* Packet filtering for digipeater or Internet Gateway.
* Separate raw packet decoder: ``decode_aprs``.
* Support for UTF-8 character set.
* Runs in three different environments:

 * Microsoft Windows XP or later.  Pentium 3 or equivalent or later.
 * Linux, regular PC or single board computers such as Raspberry Pi.
 * Macintosh OS X.

New in version 1.4
------------------
 
* Traditional "connected" mode packet.  See Chapter 10.
* New filter and default behavior for IGate messaging.  See new document "Successful-APRS-IGate-Operation.pdf" with IGate background, configuration, and troubleshooting tips.
* IBEACON for sending IGate statistics.
* The top speed of 9600 bps has been increased to 38400. See "Going-beyond-9600-baud.pdf" for more details.
* Translation of position reports and objects into waypoint sentences: $GPWPL, $PGRMW, $PMGNWPL, $PKWDWPL.

See the CHANGES.md file for revision history.


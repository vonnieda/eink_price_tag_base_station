# Hardware
- 1x ESP32 WROOM-32 Dev Board: [Amazon.com: ACEIRMC D1 Mini NodeMCU ESP32 ESP-WROOM-32 WLAN WiFi Bluetooth IoT Development Board 5V Compatible for Arduino (5pcs) : Electronics](https://www.amazon.com/gp/product/B08PNWB81Z/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

- 1x CC1101 RF Module: [Amazon.com: 2X CC1101 Wireless RF Transceiver 315/433/868/915MHZ + SMA Antenna Wireless Module : Electronics](https://www.amazon.com/dp/B01DS1WUEQ?psc=1&ref=ppx_yo2ov_dt_b_product_details)

- 1x 989 MHz Antenna with SMA connector: I use my FlightAware antenna but anything should work.

- 7x female to female Dupont jumpers:
- 
- Chroma29 displays: https://www.ebay.com/itm/314586847303

- Chroma74 displays: https://www.ebay.com/itm/155039383396

# Software

This is the software being used: https://github.com/atc1441/E-Paper_Pricetags

It doesn't compile as it is now due to library dependencies, and I updated it to fix a few issues. I'll push that up soon.

# Process

1. Hook up the ESP32 to the CC1101 board. See pinout below.
2. Attach antenna.
3. Flash ESP32 using Platformio.
4. Look for ESP32 fallback WiFI AP and connect.
5. Enter WiFi infoz.
6. Reconnect to the new IP of the ESP32.
7. Log area at bottom should start showing things happening.



# esp8266-moisture-sensor

The endgoal of this project is to have a moisture sensor connected to Home Assistant using an esp8266. I'm moving out soon and I'll probably have a couple of plants in the house, so this seemed like a fun project to pickup. Note that there are a lot of open endings en decisions to be made...

## Research topics

- Power source
    - 18650
    - Coincell battery
    - Solar
    - Other?
- Connection
    - Wifi
    - ESP Now
        - Sensing device will be more power efficient +
        - Need to have another esp listening -
- Cathodes
    - Galvanized nails
    - Graphite (from pencils?)
    - Cheap Aliexpress
- Current delivery to Cathodes
    - Need to turnoff the current to the cathodes to limit the ocidation. Even with graphite it's still good practice. This should be easily possible using a transistor.

## Resources used

- https://www.youtube.com/watch?v=udmJyncDvw0 (also see comment section)
- https://arduinodiy.wordpress.com/2020/08/24/soil-moisture-sensors/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-1/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-2/
    - https://arduinodiy.wordpress.com/2016/02/25/a-capacitive-soil-humidity-sensor-part-3/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-4/

### Possible Zigbee version for the far future:

- https://de.aliexpress.com/item/32803052003.html
- https://de.aliexpress.com/item/32803335623.html
- https://github.com/Koenkk/Z-Stack-firmware
- https://github.com/formtapez/ZigUP/
- https://ptvo.info/
- https://www.ti.com/lit/an/swra615a/swra615a.pdf
- https://modkam.ru/?p=1220
- https://modkam.ru/?p=1700
    - https://github.com/diyruz/flower
- https://e2e.ti.com/support/wireless-connectivity/zigbee-and-thread/f/158/t/746331?tisearch=e2e-sitesearch&keymatch=faq%3Atrue
  - https://www.ti.com/lit/an/swra615a/swra615a.pdf?ts=1600238890412
  - https://www.ti.com/lit/wp/swra635/swra635.pdf?ts=1600238951750
  - http://dev.ti.com/tirex/explore/node?a=pTTHBmu__&node=AGJ1w770NgmECHXAzhAYMw__pTTHBmu__LATESThash=item2d12eb2c90:g:h3EAAOSwR5BfGVXo
  - https://e2e.ti.com/support/wireless-connectivity/zigbee-and-thread/f/158/t/906365
  - https://github.com/Koenkk/zigbee2mqtt/issues/1429
  - https://electrolama.com/projects/zig-a-zig-ah/
    - > CC2652R: 2.4GHz only multi-protocol (Zigbee, Bluetooth, Thread, ...) wireless MCU. Cortex-M0 core for radio stack and Cortex-M4F core for application use, plenty of RAM. Free compiler option from TI. zzh uses this chip.
    - Hopefully the "Free compiler option from TI" part also counts for the CC2652P: CC2652R with a built-in RF PA. Not pin or firmware compatible with
  - https://www.ti.com/product/CC2652P (CC2652P is the latest affortable TI chip with integrated power amplifier)
  - https://www.ebay.nl/itm/E72-2G4M20S1E-CC2652P-2-4G-zigbee-20dBm-700m-bluetooth-5-0-PCB-BLE-module/193590930576?

# esp8266-moisture-sensor

The endgoal of this project is to have a moisture sensor connected to Home Assistant using an esp8266. As I'm moving out soon and I'll have a couple of plants in the house this seemed like a fun project. Note that there are a lot of open endings en decisions to be made...

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
    - Need to turnoff the current to the cathodes to limit the ocidation. Even with graphite it's still good practice. This is possible using a transistor.

## Resources used

- https://www.youtube.com/watch?v=udmJyncDvw0 (also see comment section)
- https://arduinodiy.wordpress.com/2020/08/24/soil-moisture-sensors/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-1/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-2/
    - https://arduinodiy.wordpress.com/2016/02/25/a-capacitive-soil-humidity-sensor-part-3/
    - https://arduinodiy.wordpress.com/2018/06/28/a-capacitive-soil-humidity-sensor-part-4/
# LilyGo-EPD-4-7-OWM-Weather-Display
Using the LilyGo EPD 4.7" display to show OWM Weather Data

This is a fork of the fork of [DzikuVx's GLPV3'd LilyGo OWM port](https://github.com/DzikuVx/LilyGo-EPD-4-7-OWM-Weather-Display) from [G6ED](https://github.com/G6EJD/).  Original [README.MD](./src/README.md)

Revisions of this fork using the "onecall" API from openweathermap.org to display hourly forecast instead of original 3-hour "forecast" API.  Can be set by the 'use_hourly_forecast' flag in the INO file.

Migrated the project from Arduino to PlatformIO as I like projects based on PIO.

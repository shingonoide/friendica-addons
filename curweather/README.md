Current Weather
===============

If activated by your user this addon adds a widget to the users network tab
sidebar showing current weather informations (temperature, relative humidity,
wind conditions and preassure) from [OpenWeatherMap](http://openweathermap.org).
The user can configure the location as e.g. *Berlin,DE* or the zip code "14476,DE".

The language for the request at OpenWeatherMap is set to the UI language of
friendica. If the string for the description of the current weather conditions
is available in this language depends on OpenWeatherMap, fallback is english.

**You should get an APPID from OpenWeatherMap if you want to use this widget.**
You can register [here](http://openweathermap.org/register).

Credits
-------

* Tony Baldwin wrote the original addon for Friendica
* Fabio Comuni
* Tobias Diekershoff switched the sources to OpenWeatherMap after the original
  provider turned off support for locations outside of the USA.

Known Issues
------------

* Localization does not work (Jul 15) data requested via XML are EN only but
  have moew information available compared to data requested via JSON which is
  available in other languages as well. Right now we use the XML dataset

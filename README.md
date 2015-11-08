# Infopartment

![](http://all.utou.ch/iot/iothack15/infopartment-4.png)

a project started at [NZZ VR Hackdays](http://hackdays.nzz.ch/vr15/)

[immersive data visualisation](http://arxiv.org/pdf/1410.7670.pdf) techniques allow exploring datasets within a rich 3D environment. we made a VR project from our own interior design files representing a family apartment, as well as 3D models generated from open data sources. this was all done in Blender and its built-in Python API, the result being combined in Unity for export to Google Cardboard and other VR devices.

We ran into issues getting our project deployed for live demo, but here you can see the work in progress, which includes the following 3D data visualisations:

**Heating energy usage in the City of Zürich**

![](http://all.utou.ch/iot/iothack15/infopartment-heizung.gif)

The twelve months of the years are represented, with time flowing past, depth indicating the change in the amount of heat consumed by the city in that month, year to year.

![](http://all.utou.ch/iot/iothack15/infopartment-2.png)

Here is how this looks in a Virtual Reality display.

**Electricity production sources in Switzerland**

![](http://all.utou.ch/iot/iothack15/infopartment-energywaves.png)

Water, Nuclear, Thermal and "Misc. Renewable" energy sources are represented in this time stream visualisation that works in a similar way to the one above.

![](http://all.utou.ch/iot/iothack15/infopartment-3.png)

Again, here is a screenshot from Cardboard SDK / Unity.

**Television consumption in Switzerland**

![](http://all.utou.ch/iot/iothack15/infopartment-ribbons.png)

French, German and Italian regions are represented in these ribbons, showing how TV viewing has changed over the past decades.

**Data sources**

![](http://all.utou.ch/iot/iothack15/infopartment-sketch.png)

A sketch showing the initial idea, a plurality of datasets in one device.

## Data sources

- [Schweizerische Gesamtenergiestatistik 1990-2014](http://www.bfe.admin.ch/dokumentation/publikationen/index.html?start=0&lang=de&marker_suche=1&ps_text=Schweizerische+Gesamtenergiestatistik&ps_nr=&ps_date_day=Tag&ps_date_month=Monat&ps_date_year=Jahr&ps_autor=&ps_date2_day=Tag&ps_date2_month=Monat&ps_date2_year=Jahr&ps_show_typ=no&ps_show_kat=no) - Swiss Federal Office of Energy SFOE
- [Kennzahlen Fernsehnutzung 2000-2014](http://www.bfs.admin.ch/bfs/portal/de/index/themen/16/03/key/ind16.indicator.16010305.160105.html) - Federal Statistical Office, Neuchâtel 2015
- [Heizgradtage Stadt Zürich 1990-2014](https://www.stadt-zuerich.ch/heizgradtage) (shown above)

## Team

- [Alève Mine](http://alevemine.com)
- [Amir Maslic](https://github.com/tumid)
- [Oleg Lavrovsky](https://github.com/loleg)
- Stefan Bösch
- Olga

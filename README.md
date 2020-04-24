# GraphHopper Open Traffic Collection

Collections of URLs pointing to traffic information portals which contain open data or at least data which is free to use

## Europe

* Italy:
  * [Bolzano](http://traffic.bz.it/) documentation [here](http://ipchannels.integreen-life.bz.it/doc/), repo [here](https://github.com/tis-innovation-park/BZtraffic). See [#1](https://github.com/graphhopper/open-traffic-collection/pull/1)
  * South Tyrol: [traffic reports](https://www.europeandataportal.eu/data/#/datasets/p_bz-webservices-southtyrolean-trafficreport-currentsituation), [mountain pass conditions and closures](https://www.europeandataportal.eu/data/#/datasets/p_bz-webservices-southtyrolean-trafficreport-mountainroadsandpasses), [roadworks and closures](https://www.europeandataportal.eu/data/#/datasets/p_bz-webservices-southtyrolean-trafficreport-works-closings). They also advertise [reports from neighboring regions](https://www.europeandataportal.eu/data/#/datasets/p_bz-webservices-southtyrolean-trafficreport-outofprovince) but the feed seems to be empty. Available custom GML, JSON or CSV formats.
  * [Turin, Italy](http://opendata.5t.torino.it/get_fdt) documentation [here](http://www.5t.torino.it/wp-content/uploads/2016/04/flussi_traffico_rt.pdf). See [#13](https://github.com/graphhopper/open-traffic-collection/issues/13)
* Germany:
  * [Cologne, Germany](http://www.offenedaten-koeln.de/dataset/verkehrskalender-der-stadt-k%C3%B6ln), CC BY 3.0, traffic flow. See this [blog post](https://www.graphhopper.com/blog/2015/04/08/visualize-and-handle-traffic-information-with-graphhopper-in-real-time-for-cologne-germany-koln/)
  * [Jena](https://opendata.jena.de/group/mobilitat)
  * [Darmstadt](https://darmstadt.ui-traffic.de/faces/TrafficData.xhtml)
  * [Hamburg](http://suche.transparenz.hamburg.de/dataset/geo-online-portal-hamburg), [WFS Daten](https://geodienste.hamburg.de/HH_WFS_Verkehr_opendata?REQUEST=GetCapabilities&SERVICE=WFS)
  * [Nordrhein-Westfalen](https://open.nrw/dataset/verkehrszentrale-verkehrsinformationen-der-viz-nrw-fuer-nordrhein-westfalen-1476687235163) and [other data](https://open.nrw/dataset/verkehrszentrale-verkehrslage-los-1476688071631), both in Datex-II format.
  * [Entire DE (broken)](https://www.mcloud.de/web/guest/suche/-/results/detail/verkehrsdatenautomatischedauerzhlstellen) traffic count only
  * [Entire DE BASt](https://www.bast.de/BASt_2017/DE/Verkehrstechnik/Fachthemen/v2-verkehrszaehlung/Daten/2017_1/Jawe2017.html?nn=1819490) traffic count only
  * Long-term roadworks on motorways in Datex-II format, some data sets also cover other national roads:
    * [Brandenburg](http://data-run.info/BASt-MDM-Interface/srv/2873004/clientPullService?subscriptionID=2873004)
    * [Baden-Württemberg](http://data-run.info/BASt-MDM-Interface/srv/2873002/clientPullService?subscriptionID=2873002)
    * [Bayern](http://data-run.info/BASt-MDM-Interface/srv/2873003/clientPullService?subscriptionID=2873003)
    * Bremen: [this](http://data-run.info/BASt-MDM-Interface/srv/2875000/clientPullService?subscriptionID=2875000) and [this](http://data-run.info/BASt-MDM-Interface/srv/2875001/clientPullService?subscriptionID=2875001) (these seem to be two distinct data sets)
    * Hessen: [Long-term](http://data-run.info/BASt-MDM-Interface/srv/2873006/clientPullService?subscriptionID=2873006) and [short-term](http://data-run.info/BASt-MDM-Interface/srv/2867001/clientPullService?subscriptionID=2867001) roadworks
    * [Hamburg](http://data-run.info/BASt-MDM-Interface/srv/2873005/clientPullService?subscriptionID=2873005)
    * [Mecklenburg-Vorpommern](http://data-run.info/BASt-MDM-Interface/srv/2874000/clientPullService?subscriptionID=2874000)
    * [Schleswig-Holstein](http://datarun2018.de/BASt-MDM-Interface/srv/2877000/clientPullService?subscriptionID=2877000)
    * [Saarland](http://data-run.info/BASt-MDM-Interface/srv/2876000/clientPullService?subscriptionID=2876000)
    * [Sachsen](http://data-run.info/BASt-MDM-Interface/srv/2874002/clientPullService?subscriptionID=2874002)
    * [Sachsen-Anhalt](http://data-run.info/BASt-MDM-Interface/srv/2874003/clientPullService?subscriptionID=2874003)
    * [Thüringen](http://data-run.info/BASt-MDM-Interface/srv/2874004/clientPullService?subscriptionID=2874004)
  * [Frankfurt (Main)](http://data-run.info/BASt-MDM-Interface/srv/2866000/clientPullService?subscriptionID=2866000) traffic situation in Datex-II format
  
  Most of the Datex-II sets rely on Alert-C for location coding and requires the current LCL for Germany, which can be obtained free of charge but does not permit redistribution of the tables themselves. Many data sets indicate an incorrect location table number (LTN) but location codes will decode correctly when overriding the LTN indicated in the Datex-II stream.
* UK:
  * [Entire UK](http://www.dft.gov.uk/traffic-counts/) traffic count only
  * [Here](https://data.gov.uk/dataset/dft-eng-srn-routes-journey-times) seems to be some traffic flow data.
  * [Scotland](https://trafficscotland.org/datex/): various Datex-II data sets, registration required.
* Sweden:
  * [Gothenbury](http://www.statistik.tkgbg.se/)
  * [Various data sets in Datex-II](https://www.trafikverket.se/tjanster/Oppna_data/oppna-data-vi-erbjuder/), registration required
* [Switzerland](https://www.astra.admin.ch/astra/en/home/dokumentation/verkehrsdaten.html) traffic count only
* France
  * [Traffic count](https://www.quandl.com/data/INSEE?keyword=traffic)
  * [Datex-II event data](http://diffusion-numerique.info-routiere.gouv.fr/acces-aux-donnees-evenementielles-datex-2-r13.html), requires registration
* [Historic Road data in EU](http://open-data.europa.eu/en/data/dataset/4t2lYOaJNRsEgDA37hrUgg)
* [Netherlands](http://83.247.110.3/ndwOpenAVG/Default.aspx) via the NDW. FTP-Server for data and measurements is ftp://83.247.110.3/ , see [#2](https://github.com/graphhopper/open-traffic-collection/issues/2). Feeds are also available at http://opendata.ndw.nu/. Specifically:
  * `brugopeningen` has time tables for movable bridges, indicating when they are opened (i.e. raised) and thus impassable for road traffic
  * `gebeurtenisinfo`: traffic messages, e.g. traffic jams, wrong-way drivers, closures, detours and weather conditions
  * `incidents`: Breakdowns and accidents
  * `srti` has safety-related traffic information
  * `wegwerkzaamheden`: roadworks and event-related traffic measures
  * There are also various measured data publications, indicating traffic flow, speed, travel times and queues.
  
  The Datex-II situation reports rely heavily on Alert-C for location encoding. However, they do not use the regular Alert-C location code list for the Netherlands, but the [VILD](https://docs.ndw.nu/en/sb/algemeen/specialisatie/VILD.html), which has incompatible lcoation codes. It can be downloaded from https://www.ndw.nu/documenten/nl/#cat_2. A semi-automatic process to convert the VILD to a Location Table Exchange Format, as understood by Alert-C toolchains, is described [here](https://gitlab.com/traffxml/vild2ltef).
 * Lithuania:
   * [traffic count](http://lakd.lrv.lt/lt/atviri-duomenys)
   * [restrictions](http://restrictions.eismoinfo.lt/): Roadworks, road closures and restrictions, incidents; JSON-based format similar to Waze CIFS. More information at http://eismoinfo.lt > Open data/Atviri duomenys.
   * [intensity](https://old.eismoinfo.lt/traffic-intensity-service): Real-time traffic flow data. More information at http://eismoinfo.lt > Open data/Atviri duomenys (note that the URL has changed since). Note that coordinates for road segments are in LKS94 (EPSG:3346).
* Belgium:
  * [Brussels Region](http://opendatastore.brussels/en/dataset/traffic-count): real-time traffic counting
  * [Roadworks](http://www.verkeerscentrum.be/uitwisseling/datex2full) in Datex-II format. Relies on Alert-C for location decoding; ignore the `alertCLocationTableNumber` indicated in the Datex-II stream and use the default table for Belgium.
* Poland:
  * [Traffic events](https://www.gddkia.gov.pl/dane/zima_html/utrdane.xml) in a custom XML format. Georeferencing is based on distance markers along the road; the WGS84 coordinate pair which accompanies the message is only suitable for display and can be significantly off. [traff-gddkia](https://gitlab.com/traffxml/traff-gddkia) is an attempt at a FOSS Java library which parses the data.
  * The [NAP](https://kpd.gddkia.gov.pl/) has Datex-II traffic data; registration is required to get access.
* [Austria](https://services2.asfinag.at/web/trafficdata/documents): Various data sets in Datex-II format. Requires registration; some packages are free of charge, others only for a fee.
* [Czechia](http://registr.dopravniinfo.cz/en/): Feeds for common traffic information, restrictions and weather. Available in both Datex-II and a custom format called DDR XML. Requires registration (free of charge) and running a server, to which the service will then push updates as they occur.
* [Estonia](https://tarktee.mnt.ee/#/en/datex): road safety, traffic restrictions and real time traffic flow in Datex-II format. Location referencing seems to rely mainly on distance markers (on which data on OSM is scarce); WGS84 is used for single-point locations only; Alert-C is not used. Requires registration, free of charge.
* Finland:
  * [Digitraffic](https://www.digitraffic.fi/en/road-traffic/) has several data sets, some in a custom JSON format, others in Datex-II level C
  * Roadworks in [Datex-II](https://aineistot.vayla.fi/roadworks/roadworks_d2.xml) and [InfoXML](https://aineistot.vayla.fi/roadworks/roadworks_infoxml.xml) format. The Datex-II set relies on Alert-C for location referencing.
  * [Weight restrictions](https://aineistot.vayla.fi/painorajoitukset/painorajoitukset_d2.xml) in Datex-II, relies on Alert-C for location referencing.
* [Luxembourg](http://www.cita.lu/info_trafic/datex/situationrecord): Traffic events in Datex-II format. Relies on Alert-C for location referencing.
* [Norway](https://www.vegvesen.no/om+statens+vegvesen/om+organisasjonen/apne-data/Datex/publikasjoner): Various data sets in Datex-II format, requires registration. Relies on Alert-C for location referencing, the LCL can be downloaded from the site.
* [Slovenia](https://www.promet.si/portal/en/etd.aspx): various data sets in Datex-II format, requires registration.
* [Catalonia](http://www.gencat.cat/transit/opendata/incidenciesGML.xml): traffic events, custom XML format.
  
Many EU data sets are available at the [European Data Portal](http://www.europeandataportal.eu/data/en/group/transport?q=traffic)

EU authorities rely heavily on the Datex-II format for data exchange. Many of these data sets use Alert-C for location referencing and require a location code list (LCL) for location lookup.
* In most cases the LCL can be obtained free of charge (at least for the countries which rely on Alert-C in their Datex-II feeds) and can be incorporated in applications, devices and information services, but some impose restrictions on redistribution of the raw tables. The [OSM Wiki](https://wiki.openstreetmap.org/wiki/TMC#Available_datasets) has a list of sources where LCLs can be obtained.
* A FOSS Java library for location decoding is available here: [traff-libalertclocation](https://gitlab.com/traffxml/traff-libalertclocation) Decoding an Alert-C location requires the country code, location table number (LTN) and location code.
* Some sources supply an incorrect LTN; ignore the `alertCLocationTableNumber` elements in the data and use the correct one instead. (The only exception being the Netherlands, see above.)

## Australia

 * [New South Wales](http://www.rms.nsw.gov.au/about/access-to-information/access-to-data.html) (looks unfree)
 * [Victoria](http://api.vicroads.vic.gov.au/)

## USA

Several entries are take from [this stackexchange answer](http://opendata.stackexchange.com/a/1772/12662)

* [nationwide](http://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm)
* [Alabama](https://www.dot.state.al.us/maweb/trafficMonitoring/trafficMonitoring.html)
* [Arizona](http://www.azdot.gov/planning/DataandAnalysis)
* [Arlington](http://www.arlingtonva.us/Departments/EnvironmentalServices/dot/traffic/counts/EnvironmentalServicesCounts.aspx)
* [California](http://traffic-counts.dot.ca.gov/)
* [Chicago](https://data.cityofchicago.org/browse?tags=traffic) or [one specific set](https://data.cityofchicago.org/Transportation/Average-Daily-Traffic-Counts/pfsx-4n4m)
* [Colorado](http://dtdapps.coloradodot.info/otis)
* [Delaware Valley](http://www.dvrpc.org/webmaps/trafficcounts/)
* [Florida](http://www.dot.state.fl.us/planning/statistics/trafficdata/)
* [Indiana](http://www.in.gov/indot/2720.htm)
* [Maine](http://www.maine.gov/mdot/traffic/ytc/)
* [Massachusetts](http://www.massdot.state.ma.us/highway/TrafficVolumeCounts.aspx)
* [Michigan](http://www.michigan.gov/mdot/0,4616,7-151-9615---,00.html) (seems to be no longer available)
* [Minnesota](http://www.dot.state.mn.us/traffic/data/)
* [New York City](https://data.cityofnewyork.us/Transportation/Real-Time-Traffic-Speed-Data/xsat-x5sa) and [New York](https://www.dot.ny.gov/highway-data-services)
* [North Carolina](http://www.ncdot.gov/projects/trafficsurvey/)
* [Ohio](http://www.dot.state.oh.us/Divisions/Planning/TechServ/traffic/Pages/Traffic-Count-Reports-and-Maps.aspx)
* [Oregon](http://www.oregon.gov/ODOT/td/tdata/Pages/tsm/tvt.aspx)
* [South Carolina](http://www.scdot.org/getting/trafficcounts.aspx)
* [Tennessee](http://www.tdot.state.tn.us/projectplanning/adt.asp) (seems to be no longer available)
* [Washington](http://www.wsdot.wa.gov/mapsdata/travel/annualtrafficreport.htm)
* [Wisconsin](http://wisconsindot.gov/Pages/projects/data-plan/traf-counts/default.aspx)
 
## Canada

* [British Columbia](http://www.th.gov.bc.ca/trafficData/)

## Selected

* [Open Traffic Data project](http://www.worldbank.org/en/news/feature/2016/12/19/open-traffic-data-to-revolutionize-transport)
* [OpenTraffic.io](http://opentraffic.io/) -> seems inactive
* [MDM-Portal](http://www.mdm-portal.de/) (coverage will be Europe, free to use): Düsseldorf Germany, NRW Germany, ...
* [Datex2 Portal](http://www.datex2.eu/datex-node/), See more information about the UK data [here](http://dalelane.co.uk/blog/?p=1450)
* [NYC Taxi and Limousine Commission](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml): NYC taxi data, dating back to 2009. See also [this blog post](http://toddwschneider.com/posts/analyzing-1-1-billion-nyc-taxi-and-uber-trips-with-a-vengeance/) and this [github repository](https://github.com/toddwschneider/nyc-taxi-data)

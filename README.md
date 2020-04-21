# GraphHopper Open Traffic Collection

Collections of URLs pointing to traffic information portals which contain open data or at least data which is free to use

## Europe

* [Bolzano, Italy](http://traffic.bz.it/) documentation [here](http://ipchannels.integreen-life.bz.it/doc/), repo [here](https://github.com/tis-innovation-park/BZtraffic). See [#1](https://github.com/graphhopper/open-traffic-collection/pull/1)
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
* [Entire UK](http://www.dft.gov.uk/traffic-counts/) traffic count only, but [here](https://data.gov.uk/dataset/dft-eng-srn-routes-journey-times) seems to be some traffic flow data.
* [Gothenbury, Sweden](http://www.statistik.tkgbg.se/)
* [Switzerland](https://www.astra.admin.ch/astra/en/home/dokumentation/verkehrsdaten.html) traffic count only
* [France](https://www.quandl.com/data/INSEE?keyword=traffic) traffic count only
* [Historic Road data in EU](http://open-data.europa.eu/en/data/dataset/4t2lYOaJNRsEgDA37hrUgg)
* [Netherlands](http://83.247.110.3/ndwOpenAVG/Default.aspx) via the NDW. FTP-Server for data and measurements is ftp://83.247.110.3/ , see [#2](https://github.com/graphhopper/open-traffic-collection/issues/2)
 * [Lithuania](http://lakd.lrv.lt/lt/atviri-duomenys) traffic count only 
 * [Belgium](http://opendatastore.brussels/en/dataset/traffic-count) Real-time traffic counting in the Brussels Region.
  
Many EU data sets are available at the [European Data Portal](http://www.europeandataportal.eu/data/en/group/transport?q=traffic)

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

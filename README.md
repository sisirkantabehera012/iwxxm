# IWXXM
IWXXM (the ICAO Meteorological Information Exchange Model) is a data format for reporting aviation weather information
in XML/GML, and is specified in both XML Schema and Schematron.

[![Build Status](https://travis-ci.org/wmo-im/iwxxm.svg?branch=master)](https://travis-ci.org/wmo-im/iwxxm)

# Summary
IWXXM includes XML/GML-based representations for products
standardized in International Civil Aviation Organization (ICAO) Annex III and World Meteorological Organization (WMO)
No. 49, Vol II, such as METAR/SPECI, TAF, SIGMET, AIRMET, Tropical Cyclone Advisory and Volcanic Ash Advisory. IWXXM
products are used for operational exchanges of meteorological information for use in aviation.

Unlike the traditional forms of the ICAO Annex III / WMO No. 49 products (referred to as Traditional Alphanumeric Codes,
or TAC), IWXXM is not intended to be directly used by pilots. IWXXM is designed to be consumed by software acting on
behalf of pilots, such as display software.

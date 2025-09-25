# GOFS

The General On-Demand Format Specification lite (GOFS) allows on-demand service providers to define their service in a lightweight format that can be consumed by transport applications in an interoperable way.

GOFS, as an offshoot of the GOFS project, is meant to be compatible with GTFS-OnDemand while offering more restricted functionalities. GOFS defines a lightweight format for purely on-demand transport services to provide information about their offering, much like the General Transit Feed Specification (GTFS) exists for public transit and the General Bikeshare Feed Specification (GBFS) exists for bikeshare, shared e-scooters, carshare, and other free-floating, self-service options.  GOFS is intended to have as much common ground as possible with [GTFS](https://github.com/google/transit/) and [GBFS](https://github.com/NABSA/gbfs) when the context allows it. 

GOFS supports on-demand services:
- without fixed routes
- operated from zone to zone
- available to anyone 
- that can be ordered in real time.

Examples of supported services include: ridehail (like taxis or Uber), on-demand microtransit (like [Metro Micro](https://micro.metro.net) or [DRT On Demand](https://www.durhamregiontransit.com/en/travelling-with-us/planning-your-travel.aspx#On%20Demand)) and paratransit. 

Unsupported services include fixed or flexible public transit services where a schedule is defined (GTFS and GTFS-Flex support those use cases).

Future GOFS extensions may support on-demand services:
- operated from curb-to-curb, stop-to-stop, or door-to-door
- providing private and/or shared trips
- that can be booked in advance.

GOFS is a work in progress, there are currently important missing functionalities like accurate pricing, travel time estimations, etc. Questions or comments can be sent to [gofs@mobilitydata.org](mailto:gofs@mobilitydata.org).

## GOFS JSON schema
A JSON schema which can be used to validate GOFS feeds can be found [here](schema/).

# HERE-Map-API

This doc is to clear some critical points in HERE map API understanding.

## Fleet Telematics Route Matching

** Currently my understanding is: 

### response:

* RouteLinks: road links

linkId: +-

functionalClass: Required by PDE

shape: string (lat/lon coordinates array) Required by PDE

linkLength: straight length between shape points (meter)

confidence: for this link

mSecToReachLinkFromStart

offset






* TracePoints: trace points

lat (original)
lon (original)
elevation (original)
speedMps (original)
headingDegreeNorthClockwice(original)

latMatched: The coordinated is guaranteed to fit onto map road network, where the map shape points are connected by straight lines.

lonMatched: The coordinated is guaranteed to fit onto map road network, where the map shape points are connected by straight lines.

linkIdMatched: +-

routeSeqNrMatched: count matched links 0,1,2,3..

timestamp

matchDist: distance between the original trace point and the matched coordinate (meter)

headingMatched:

minError

confienceValue: confidence for this point match

matchOffsetOnLink


# Fleet Telematics Advanced Data Sets (PDE)










# BLACKHOLE BGP Community #
## Goal ##
The introduction of a well-known Border Gateway Protocol (BGP) community for destination-based blackholing in IP networks.  This well-known advisory transitive BGP community named BLACKHOLE allows an origin AS to specify that a neighboring network should discard any traffic destined towards the tagged IP prefix.

## Status ##
* RFC-to-be https://www.rfc-editor.org/authors/rfc7999.txt
* Datatracker: https://datatracker.ietf.org/doc/draft-ietf-grow-blackholing/

## Supporting ISPs and IXPs ##
### Supporting ISPs

### Supporting IXPs
| IXP | Information |
|-----| ----------- |
| [DE-CIX](https://www.de-cix.net) FRA, NYC, MAD, DUS, MUC, HAM, IST, PMO, MRS  | https://de-cix.net/en/services/globepeer/blackholing |
| NYIIX | |

## Supporting BGP Speakers ##
| BGP Speaker   | Implementation Status |
| ------------- | ------------- |
| [BIRD](http://bird.network.cz/)  | Open |
| [GoBGP](https://github.com/osrg/gobgp) | [Done](https://github.com/osrg/gobgp/issues/1136) |
| [OpenBGPD](http://www.openbgpd.org/) | (Done)[http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/bgpd/bgpd.h.diff?r1=1.290&r2=1.291&f=h] - Usage hint: "allow from any community BLACKHOLE set nexthop blackhole" |
| [Nokia](https://networks.nokia.com/) | Requested |
| [Cisco](https://www.cisco.com/) | Open |
| [Juniper](https://www.juniper.com/) | Open |
| [Brocade](https://www.brocade.com/) | Open |
| [Huawi](huawei.com) | Open |

## History ##
* Discussions started during [EURO-IX](http://www.euro-ix.net)
* ...
* Working Group Last Call:

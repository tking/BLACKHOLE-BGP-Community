# BLACKHOLE BGP Community #
## Goal ##
The introduction of a well-known Border Gateway Protocol (BGP) community for destination-based blackholing in IP networks.  This well-known advisory transitive BGP community named BLACKHOLE allows an origin AS to specify that a neighboring network should discard any traffic destined towards the tagged IP prefix.

## Status ##
* Task accomplished: RFC 7999: https://tools.ietf.org/html/rfc7999
* Datatracker: https://datatracker.ietf.org/doc/draft-ietf-grow-blackholing/

## Supporting ISPs and IXPs ##
If you want to be listed please drop me mail: thomas.king@de-cix.net

### Supporting ISPs
| ISP | Information |
| --- | ----------- |
| [KPN (AS286)](http://www.kpn-international.com/ip-transit) | https://as286.net/AS286-communities.html |
| [SysEleven (AS25291)](http://www.syseleven.de/) | https://isp.syseleven.net/communities/#communities-for-customers |
| [Strato AG (AS6724)](http://www.strato.de) | |
| [Individual Network Berlin e.V. (AS29670)](https://in-berlin.de/) | |
| [Coloclue (AS8283)](http://coloclue.net/) | |
| [Fusix Networks (AS57866)](http://fusix.nl/) | |
| [BelWü (AS553)](http://belwue.de) | |

### Supporting IXPs
| IXP | Information |
| --- | ----------- |
| [DE-CIX](https://www.de-cix.net) FRA, NYC, MAD, DUS, MUC, HAM, IST, PMO, MRS, DFW  | https://de-cix.net/en/services/globepeer/blackholing |
| [NYIIX](http://www.nyiix.net) | http://www.nyiix.net/rtbh/ |
| [CIX.HR](https://www.cix.hr) | https://www.cix.hr/o-cix-u/infrastruktura/route-server |
| [Community-IX](https://www.community-ix.de) | https://www.community-ix.de/technik/ |
| [LAIIX](http://www.laiix.net/)| http://www.laiix.net/rtbh/ |
| [Equinix](https://ix.equinix.com/) Ashburn, Atlanta, Chicago, Dallas, Los Angeles, Miami, New York, Palo Alto, San Jose, Seattle, Toronto, Vienna, Geneva, Paris, Zurich, Hong Kong, Melbourne, Osaka, Singapore, Sydney, Tokyo | http://www.sanog.org/resources/sanog28/SANOG28-Conference_RTBH-Safiudeen.pdf |
| [MSK-IX](http://www.msk-ix.ru/en/) Moscow, St.-Petersburg, Rostov-on-Don, Stavropol, Samara, Kazan, Ekaterinburg, Novosibirsk, Vladivostok | http://kb.msk-ix.ru/en/ix/services/route-server/#ddos |
| [SIX](https://www.seattleix.net/) Seattle | https://www.seattleix.net/blackholing |
| [France IX](https://www.franceix.net) Paris and Marseille | https://www.franceix.net/en/technical/blackholing/ |

## Supporting Anti-DDoS Software ##
| Software | Implementation Status | Information |
| ----- | ----------- | ------ |
| [FastNetMonDE-CIX](https://github.com/pavel-odintsov/fastnetmon) | [Done](https://github.com/pavel-odintsov/fastnetmon/commit/b86b2de12c64fba5b2c948567ac1c20e0271e677) | [Description](https://ciscodude.net/2017/01/01/bgp-blackhole-community/) |

## Supporting BGP Speakers ##
| BGP Speaker   | Implementation Status |
| ------------- | ------------- |
| [BIRD](http://bird.network.cz/)  | Done |
| [GoBGP](https://github.com/osrg/gobgp) | [Done](https://github.com/osrg/gobgp/issues/1136) |
| [OpenBGPD](http://www.openbgpd.org/) | [Done](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.sbin/bgpd/bgpd.h.diff?r1=1.290&r2=1.291&f=h) - Usage hint: "allow from any community BLACKHOLE set nexthop blackhole" |
| [ExaBGP](https://github.com/Exa-Networks/exabgp) | [Done](https://github.com/Exa-Networks/exabgp/commit/12ff1f9575172a0872917185df578bce6adc4e18) |
| [Nokia](https://networks.nokia.com/) | Requested |
| [Cisco](https://www.cisco.com/) | Open |
| [Juniper](https://www.juniper.com/) | Open |
| [Brocade](https://www.brocade.com/) | Open |
| [Huawei](http://www.huawei.com) | Open |

## History ##
### 2014 ###
* Euro-IX tech mailing list: Discussion on commonly agreed BLACKHOLE community
* 25th Euro-IX Forum: Presentation and panel about Blackholing
* Work on an “Internet Draft” started. Authors: King, Dietzel (DE-CIX), Döring (SpaceNet), Hankins (Alu), Jiran (NIX.CZ), Kritski (NetIX), Seitz (STRATO)

### 2015 ###
* Draft of “Internet Draft” discussed on the Euro-IX tech mailing list
* “Internet Draft” submitted to IETF GROW working group
* Discussion on the GROW mailing list and during the IETF 93
* Requests from Euro-IX and GROW:
 * Also add ISPs
 * Be more specific about “Operations Recommendations”
* Call for “Working Group” adaption

### 2016 ###
* Working Group Last Call – all few changes
* Release of RFC 7999

## Special Thanks ##
* [Euro-IX](http://www.euro-ix.net)
* [GROW Working Group](https://datatracker.ietf.org/wg/grow/charter/)
* [ECO KG Gruppe Netz Infrastruktur](https://netz-infrastruktur.eco.de/) 

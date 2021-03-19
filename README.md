# OPSAWG repo for LxNM-related specifications: VPN-COMMON, L3NM, L2NM, and PM

##  A Layer 2/3 VPN Common YANG Model
This document defines a common YANG module that is meant to be reused
   by various VPN-related modules such as Layer 3 VPN and Layer 2 VPN
   Network Models.

### Common Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-vpn-common&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-vpn-common/draft-ietf-opsawg-vpn-common.txt)

## L3 VPN Network-Oriented YANG Model

The L3NM document specifies a L3VPN Network YANG Model (L3NM) to facilitate communication 
between a service orchestrator and a network
   controller/orchestrator.  Such data model provides a network-centric
   view of the L3VPN services.  The Yang model proposed is limited to
   BGP PE-based VPNs as described in RFCs 4026, 4110, and 4364.
  
### l3nm Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-l3sm-l3nm&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-L3NM/draft-ietf-opsawg-l3sm-l3nm.txt)
   
## L2 VPN Network-Oriented YANG Model
A L2VPN Network Yang Model

This document defines a YANG Data model (called, L2NM) that can be used to manage the provisioning of Layer 2 VPN services within a Service Provider Network. This YANG module provides representation of the Layer 2 VPN Service from a network standpoint. The module is meant to be used by a Network Controller to derive the configuration information that will be sent to relevant network devices.

The L2SM complements the Layer 2 Service Model (RFC8466) by providing a network-centric view of the service that is internal to a Service Provider.

### l2nm Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-l2nm&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-L2NM/draft-ietf-opsawg-l2nm.txt)

##  A YANG Model for Network and VPN Service Performance Monitoring
This document defines a YANG model for
   both Network Performance Monitoring and VPN Service Performance
   Monitoring that can be used to monitor and manage network performance
   on the topology at higher layer or the service topology between VPN
   sites.
   
### PM Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-yang-vpn-service-pm&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-vpn-pm/draft-ietf-opsawg-yang-vpn-service-pm.txt)


# Contributing

This repository relates to activities in the Internet Engineering Task Force
([IETF](https://www.ietf.org/)). All material in this repository is considered
Contributions to the IETF Standards Process, as defined in the intellectual
property policies of IETF currently designated as
[BCP 78](https://www.rfc-editor.org/info/bcp78),
[BCP 79](https://www.rfc-editor.org/info/bcp79) and the
[IETF Trust Legal Provisions (TLP) Relating to IETF Documents](http://trustee.ietf.org/trust-legal-provisions.html).

Any edit, commit, pull request, issue, comment or other change made to this
repository constitutes Contributions to the IETF Standards Process
(https://www.ietf.org/).

You agree to comply with all applicable IETF policies and procedures, including,
BCP 78, 79, the TLP, and the TLP rules regarding code components (e.g. being
subject to a Simplified BSD License) in Contributions.


## Other Resources

Discussion of this work occurs on the
[OPSAWG working group mailing list](https://mailarchive.ietf.org/arch/browse/opsawg/)
([subscribe](https://www.ietf.org/mailman/listinfo/opsawg)).  In addition to
contributions on GitHub, you are encouraged to participate in discussions there.

**Note**: Some working groups adopt a policy whereby substantive discussion of
technical issues needs to occur on the mailing list.

You might also like to familiarize yourself with other
[working group documents](https://datatracker.ietf.org/wg/opsawg/documents/).

  
# Yang validation and yang extraction from draft:

| **Master**  
|:---:|
| [![Build Status](https://travis-ci.org/IETF-OPSAWG-WG/l3nm.svg?branch=master)](https://travis-ci.org/IETF-OPSAWG-WG/l3nm.svg?branch=master) |



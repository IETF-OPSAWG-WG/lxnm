# OPSAWG repo for LxNM-related specifications: VPN-COMMON, L3NM, L2NM, PM, and SAP

##  A Network YANG Model for Service Attachment Points

This document defines a YANG data model for representing an abstract
   view of the provider network topology containing the points from
   which its services can be attached (e.g., basic connectivity, VPN,
   network slices).

### [Public version](https://datatracker.ietf.org/doc/draft-ietf-opsawg-sap/)
### [Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-sap&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-sap/draft-ietf-opsawg-sap.txt)
   
##  A Layer 2/3 VPN Common YANG Model
This document defines a common YANG module that is meant to be reused
   by various VPN-related modules such as Layer 3 VPN and Layer 2 VPN
   Network Models.

### Final version of the Common Module: [RFC9181](https://www.rfc-editor.org/rfc/rfc9181.html)

## Layer 3 VPN Network YANG Model

The L3NM document specifies a L3VPN Network YANG Model (L3NM) to facilitate communication 
between a service orchestrator and a network
   controller/orchestrator.  Such data model provides a network-centric
   view of the L3VPN services.  The Yang model proposed is limited to
   BGP PE-based VPNs as described in RFCs 4026, 4110, and 4364.
  
### Final version of the L3NM [RFC9182](https://www.rfc-editor.org/rfc/rfc9182.html)
   
## A L2VPN Network YANG Model

This document defines a YANG Data model (called, L2NM) that can be used to manage the provisioning of Layer 2 VPN services within a Service Provider Network. This YANG module provides representation of the Layer 2 VPN Service from a network standpoint. The module is meant to be used by a Network Controller to derive the configuration information that will be sent to relevant network devices.

### l2nm Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-l2nm&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-L2NM/draft-ietf-opsawg-l2nm.txt) or https://tinyurl.com/l2nm-latest

##  A YANG Model for Network and VPN Service Performance Monitoring

This document defines a YANG model for
   both Network Performance Monitoring and VPN Service Performance
   Monitoring that can be used to monitor and manage network performance
   on the topology at higher layer or the service topology between VPN
   sites.
   
### PM Module :[Diff editor copy vs published version](https://www.ietf.org/rfcdiff?url1=draft-ietf-opsawg-yang-vpn-service-pm&url2=https://raw.githubusercontent.com/IETF-OPSAWG-WG/lxnm/master/I-D-vpn-pm/draft-ietf-opsawg-yang-vpn-service-pm.txt) or https://tinyurl.com/vpn-pm-latest


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
| [![Build Status](https://travis-ci.org/IETF-OPSAWG-WG/lxnm.svg?branch=master)](https://travis-ci.org/IETF-OPSAWG-WG/lxnm.svg?branch=master) |



# 1 Attendants
•	Med Boucadir (Orange)
•	Luis Muñoz (Vodafone)
•	Oscar Gonzalez (Telefonica)
•	Samier Barguil (Telefonica)
# 2 Agenda
•	L3NM
o	Prunning
o	Relationship with the topology
# 3 Prune & hierarchy discussioon
o	Continue with the information of the service level at the network level.
o	Clarify which parameters can or not be used. (see ppt)
o	The parameters that are not used in L3NM but were useful in L3NM, decide if remove,
or leave and write in the draft they are inherited from L3SM (take decission).
o	New hierachy proposal: remove site and move site_network_acces under vpn_nodes
# 4 Topology discussions
o	Topology relationship with the Service Models.
o	Possible solutions:
--> Create UNI Topology
Node Ref
<xmp>
+--rw vpn-nodes
|  +--rw vpn-node* [vpn-node-id ne-id]
|     +--rw vpn-node-id         string
|     +--rw description?        string
|     +--rw topo-node?          -> /nw:networks/network/node/node-id"
</xmp>
•	Uni Reference
<xmp>
+--rw bearer
|     |  +--rw bearer-reference?   string {bearer-reference}?
|     |  +--rw uni-reference?      -> /nw:networks/network/node/termination-point/tp-id
</xmp>
#5 Action points
•	Discussion by email and opsawg before the next IETF DEADLINE: <2019-11-04 Mon>

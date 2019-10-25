# 1 Attendants
*	Med Boucadir (Orange)
*	Luis Muñoz (Vodafone)
*	Oscar Gonzalez (Telefonica)
*	Samier Barguil (Telefonica)

# 2 Agenda
*	L3NM
  *	Prunning
  *	Relationship with the topology

# 3 Prune & hierarchy discussion
*	Continue with the information of the service level at the network level.
*	Clarify which parameters can or not be used. (see ppt)
*	The parameters that are not used in L3NM but were useful in L3NM, decide if remove,
or leave and write in the draft they are inherited from L3SM (take decission).
*	New hierachy proposal: remove site and move site_network_acces under vpn_nodes

# 4 Topology discussions
*	Topology relationship with the Service Models.
*	Possible solutions:
  * Create UNI Topology

<em>Node Ref</em>
<pre><code>
+--rw vpn-nodes
|  +--rw vpn-node* [vpn-node-id ne-id]
|     +--rw vpn-node-id         string
|     +--rw description?        string
|     +--rw topo-node?          -> /nw:networks/network/node/node-id"
</code></pre>

<em>Uni Reference</em>
<pre><code>
+--rw bearer
|     |  +--rw bearer-reference?   string {bearer-reference}?
|     |  +--rw uni-reference?      -> /nw:networks/network/node/termination-point/tp-id
</code></pre>
#5 Action points
•	Discussion by email and opsawg before the next IETF DEADLINE: <2019-11-04 Mon>

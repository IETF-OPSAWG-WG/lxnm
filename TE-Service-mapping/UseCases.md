TE Service Mapping Use cases:

1. I want a VPN service with a given optimization criteria for all the VPN
	1.1. For example, minimum latency

2. I want a VPN service with two (or more) sets of optimization criteria for all the VPN
	2.1. For example I want a set of minimum latency paths and a set of low loss paths.

3. I want a VPN service with a given optimization criteria for some source -destination pairs (PE to PE)
	3.1. For example I want that from PE XX to PE YY a minimum latency path

4. In adition to an optimization criteria include:
	4.1. A constraint. For example less latency than 20 ms.
	4.2. A resilience property. For example, create 1+1 paths, create restorable paths, etc.
	4.3. Exclude some area/node/link/srlg from the paths asigned to the VPN. Example, enterprise VPN customers don’t want their traffic to cross certain countries or certain trans-ocean links (yes… this happens, customers are picky).

4. Instead of binding the paths to the whole VPN, explicitly indicate which traffic goes to each type of path
	5.1. The input can come from the user. E.g. the enterprise customer can tell, hey, the traffic I sent marked with XX, from IP xxx, please go with delay less than YY. These needs to be passed to the VPN creation. This policies… where do we put them?

5. Calendaring. We have received request from our business units to be able to calendar certain paths for time periods only, and schedule them in advance. E.G. enable a XX Gbps path between 3 am and 6 am.

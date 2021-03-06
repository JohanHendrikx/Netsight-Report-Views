# Extreme Management (NetSight) FlexViews for EXOS devices

Community Driven repository


## FlexViews
* [Firmware information](tpl/XOS firmware Info.tpl?raw=true)
* [Learned MAC to IP](tpl/XOS Nodealias_MAC-IP_learned.tpl?raw=true)
* [Vlan IP ports](tpl/XOS VLAN-IP-Port.tpl?raw=true)
* [L3 interface stats](tpl/XOS L3interface stats.tpl?raw=true)
* [Link Aggregation](tpl/XOS sharing.tpl?raw=true)
* [LACP Link Aggregation](tpl/XOS LACP-sharing.tpl?raw=true)


## Comments & Columns
##### Firmware information
extremeSystemID, extremeImageBooted, sysUpTime, extremeMsmFailoverCause, sysName, extremePrimarySoftwareRev, extremeSecondarySoftwareRev, extremeImageToUseOnReboot, extremeBootROMVersion

##### Learned MAC to IP
extremeFdbIpFdbPortIfIndex, extremeFdbIpFdbIPAddress, extremeFdbIpFdbMacAddress

##### Vlan IP ports
extremeVlanIfVlanId, extremeVlanIfDescr, extremeVlanIpNetAddress, extremeVlanIpNetMask, extremeVlanOpaqueTaggedPorts, extremeVlanOpaqueUntaggedPorts, extremeVlanIfType, extremeVlanIpForwardingState

##### L3 interface stats
extremeStatsPortIfIndex, ifName, extremeStatsVlanNameIndex, extremePortVlanStatsCntrType, extremePortConfigureVlanStatus, extremePortVlanTotalReceivedBytesCounter, extremePortVlanTotalReceivedFramesCounter

##### Link Aggregation
MemberPort_ifName,ifAlias,ifDescr,ifAdminStatus, ifOperStatus, MasterPort_ifName,extremePortLoadshare2Status, extremePortLoadshare2Algorithm

##### LACP Link Aggregation
ifName,ifAlias, ifDescr, ifAdminStatus, ifOperStatus, extremeLacpGroup, extremeLacpMemberPort, extremeLacpAggStatus


## Examples
* [Link Aggregation](sample/XOS sharing.png)
* [LACP Link Aggregation](sample/XOS LACP-sharing.png)


## MIBs
All necessary MIBs are included in the Extreme Management (NetSight) already.

>Be Extreme
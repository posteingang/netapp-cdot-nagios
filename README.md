# NetApp cDOT Nagios Monitoring Skripts

## About

Scripts for monitoring NetApp cDOT Clusters via NetApp Manageability SDK (Perl)

For older 7-Mode systems use my [7-Mode Scripts](https://github.com/aleex42/netapp-7mode-nagios)

## Plugins

Currently there are the following checks:

* check_cdot_aggr.pl
  Checks Aggregate Space Usage (also supports performance data)

* check_cdot_clusterconfig.sh
  bla

check_cdot_clusterlinks.pl
check_cdot_diff_snapmirror.pl
check_cdot_disk.pl
check_cdot_fcp.pl
check_cdot_global.pl
check_cdot_interfaces.pl
check_cdot_lun.pl
check_cdot_metrocluster_aggr.pl
check_cdot_metrocluster_check.pl
check_cdot_metrocluster_config.pl
check_cdot_metrocluster_state.pl
check_cdot_multipath.pl
check_cdot_quota.pl
check_cdot_rebuild.pl
check_cdot_recommendations.pl
check_cdot_snapmirror.pl
check_cdot_snapmirror_snapshots.pl
check_cdot_snapshots.pl
check_cdot_sparedisks.pl
check_cdot_volmove.pl
check_cdot_volume.pl
check_cisco_nexus_ports.pl

* check_cdot_rebuild.pl
  Checks Aggregate RAID status

* check_cdot_disk.pl
  Checks Disk Healthiness

* check_cdot_fcp.pl
  Checks FCP interface errors

* check_cdot_global.pl
  Checks Global Healthiness

* check_cdot_multipath.pl
  Checks Disk Multipathing

* check_cdot_snapmirror.pl
  Checks SnapMirror Healthiness

* check_cdot_snapshots.pl
  Checks Snapshot Age

* check_cdot_sparedisks.pl
  Checks Sparedisk Status and unowned Disks

* check_cdot_volume.pl
  Checks Space and Inode Usage of all or one specific Volume (also supports performance data)

* check_cdot_recommendation.pl 
  Checks that some Best Practises are configured

* check_cdot_clusterconfig.sh
  Checks that network configurations on all nodes are the same

* check_cdot_clusterlinks.pl
  Checks HA-Interconnects and Cluster Interfaces

* check_cdot_interfaces.pl
  Checks Interface Group Status

* check_cdot_wrong_aggregte.pl
  Checks dedicated Aggregates for SnapMirror

# Examples

For some examples have a look at my wiki: 
http://wiki.krogloth.de/index.php/NetApp_C-Mode/Monitoring


# Contact / Author

Alexander Krogloth
<git at krogloth.de>
<alexander.krogloth at noris.de> for the noris network AG.

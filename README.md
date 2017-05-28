# nagios-checks

Various nagios checks that I use.

ZFS Check(s)


root@a1ubfrogp01:~# ./check_zfs -P poolheathy

OK - zpool poolheathy is ONLINE

root@a1ubfrogp01:~# ./check_zfs -P pooldegraded


WARNING - zpool pooldegraded is DEGRADED


root@a1ubfrogp01:~# ./check_zfs -P pooloffline

CRITICAL - zpool pooloffline is UNAVAIL

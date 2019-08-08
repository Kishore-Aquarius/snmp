# snmp
Customized SNMPD and SNMPTRAPD configurations for active CPU, Disk and Memory monitoring in RHEL7 (Linux).
Any contribution to improve is welcome!

snmpd.conf: 
Heartbeat notification was contributed by Radoslaw (from /// aka. Ericsson).
Memory and Swap will be scanned every 60secs with Min Max values to generate and clear traps.
Disk(s) will be scanned every 60secs for the threshlod of 70% (includeAllDisks 30%) to generate and clear traps.
CPU/Load and processor load will be scanned every 60secs to generate and clear traps within 80-90%. 

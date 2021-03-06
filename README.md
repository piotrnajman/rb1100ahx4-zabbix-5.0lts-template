## Mikrotik RB1100AHx4 Template

** Zabbix 5.0LTS SNMP template for monitoring Mikrotik RB1100AHx4 routers. **

1. Items Health
   - Amperage
   - Power Consumption
   - PSU1 Amperage
   - PSU1 Voltage
   - PSU2 Amperage
   - PSU2 Voltage
   - Temperature
   - Voltage
2. Items Resources
   - CPU Core (discovery)
     - Core Utilisation (item prototype)
     - Core Utilisation (trigger prototype)
   - CPU Frequency
   - HDD Free
   - HDD Total
   - HDD Used
   - HDD Utilisation
   - Memory Free
   - Memory Total
   - Memory Used
   - Memory Utilisation
   - Uptime
3. Interfaces (discovery)
   - Item prototypes
     - bytes-in
     - bytes-out
     - discards-in
     - discards-out
     - error-out
     - errors-in
     - packets-in
     - packets-out
   - Graph prototypes
     - Packets on interface
     - Traffic on interface
4. Triggers
   - Disk space is critically low
   - Disk space is low
   - High memory utilization
   - PSU voltage
   - Router has been restarted
5. Graphs
   - Memory and Storage Utilisation
   - Voltages


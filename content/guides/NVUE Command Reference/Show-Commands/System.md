---
title: System
author: Cumulus Networks
weight: 410
product: Cumulus Linux
type: nojsscroll
---
<style>
h { color: RGB(118,185,0)}
</style>
## <h>nv show system</h>

Shows information about the switch, such as the hostname, Cumulus Linux verison, the switch uptime, and the timezone.

### Version History

Introduced in Cumulus Linux 5.2.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system counter polling-interval</h>

Shows the polling interval for the switch counters for both the logical and physical interfaces.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system counter polling-interval
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system cpu</h>

Shows information about the switch CPU, such as the core-count, the model, and the utilization percentage.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system cpu
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system forwarding profile-option</h>

Shows forwarding profile information.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system forwarding profile-option
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global</h>

Shows global system configuration, such as the anycast ID, anycast MAC address, fabric ID, fabric MAC address, system MAC address, routing table, VLAN, and VNI information.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global reserved</h>

Shows global reserved configuration information, such as the VLAN internal range.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global reserved
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global reserved routing-table</h>

Shows global reserved routing table information.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global reserved routing-table
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global reserved vlan</h>

Shows the reserved VLAN configuration settings.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global reserved vlan
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global reserved vlan internal</h>

Shows the reserved internal VLAN configuration settings.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global reserved vlan internal
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system global reserved vlan l3-vni-vlan</h>

Shows the reserved VLAN layer 3 VNI to VLAN mapping settings.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system global reserved vlan l3-vni-vlan
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system memory</h>

Shows information about the switch memory, such as the total amount of memory, the amount of free and used memory,and the percent of memory utilized.

### Version History

Introduced in Cumulus Linux 5.3.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system memory
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system message</h>

Shows pre- and post-login messages.

### Version History

Introduced in Cumulus Linux 5.2.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system message
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system reboot</h>

Shows system reboot information, such as the time when the switch rebooted, the reason for the reboot, and the restart mode (fast, warm, cold).

### Version History

Introduced in Cumulus Linux 5.2.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system reboot
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system reboot history</h>

Shows the system reboot history.

### Version History

Introduced in Cumulus Linux 5.0.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system reboot history
```

<HR STYLE="BORDER: DASHED RGB(118,185,0) 0.5PX;BACKGROUND-COLOR: RGB(118,185,0);HEIGHT: 4.0PX;"/>

## <h>nv show system reboot reason</h>

Shows the reason why the switch was rebooted.

### Version History

Introduced in Cumulus Linux 5.0.0

### Example

```
cumulus@leaf01:mgmt:~$ nv show system reboot reason
```

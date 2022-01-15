# My pihole config

## Scheduled pihole blocklists

The 'Block' group is used for a scheduled blocklist.  The group can be
enabled/disabled from a cron job using the provided `pihole-toggle-block`
script.

e.g.: Enable the 'Block' group in pihole from 8AM until 10PM.

```cron
0 8  * * * /home/pi/pihole/pihole-toggle-block
0 22 * * * /home/pi/pihole/pihole-toggle-block
```

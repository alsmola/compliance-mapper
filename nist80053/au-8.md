# AU-8 - Time Stamps
- Use internal system clocks to generate time stamps for audit records; and
- Record time stamps for audit records that meet \[ Assignment: granularity of time measurement \] and that use Coordinated Universal Time, have a fixed local time offset from Coordinated Universal Time, or that include the local time offset as part of the time stamp.
## Guidance
Time stamps generated by the system include date and time. Time is commonly expressed in Coordinated Universal Time (UTC), a modern continuation of Greenwich Mean Time (GMT), or local time with an offset from UTC. Granularity of time measurements refers to the degree of synchronization between system clocks and reference clocks (e.g., clocks synchronizing within hundreds of milliseconds or tens of milliseconds). Organizations may define different time granularities for different system components. Time service can be critical to other security capabilities such as access control and identification and authentication, depending on the nature of the mechanisms used to support those capabilities.
## Mapped SCF controls
- [MON-07 - Time Stamps](../scf/mon-07-timestamps.md)
- [SEA-20 - Clock Synchronization](../scf/sea-20-clocksynchronization.md)
# Data

Data are the objects that we collect from the system that
we are trying to monitor. Some examples:

* Network packets or network flow records
* System event logs
* Application logs
* Configuration data

Note that each of these is initially security neutral,
raw data.

Security events (IDS alerts, antivirus
alerts) are also data, but require special handling, because
in a sense they are also Impacts because they claim
to report something with security consequences.
Security events usually need to
pass through some of the same initial steps (Feature
Extraction and assignment to an Entity).
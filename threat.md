# Threat Detection and Prevention

`2021.08.03`

In order to preserve the integrity of data that ClearHealth stores, processes, or
transmits for customers, ClearHealth implements strong intrusion detection tools
and policies to proactively track and retroactively investigate unauthorized
access. This includes threat detection and prevention at both the network and
host level, as well as threat intelligence monitoring.

## Policy Statements

ClearHealth policy requires that:

(a) All critical systems, assets, and environments must implement real time threat
detection or prevention.

(b) Cloud devices must have minimal exposure to the internet and remain behind a private
subnet whenever possible. The private subnet must only be accessible via VPN and
protected with multi factor authentication (Duo Security).

(c) Firewall rules and access must be configured to expose the minimal amount of
services/information required to accomplish a business need. All traffic/ports must be configured.

(d) All traffic on cloud devices must be filtered and monitored.

(e) Network Architecture Diagrams of ClearHealth's infrastructure must be maintained
by IT Administrators and updated biannually and as infrastructure changes are made. 
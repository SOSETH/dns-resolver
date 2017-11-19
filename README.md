# DNS resolver role
This role configures `unbound` to provide a network (per default only localhost) with a DNSSEC-validating, caching resolver.

This role will override '/etc/resolv.conf', so take care if you want to use this on a non-server system.

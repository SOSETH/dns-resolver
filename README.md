# DNS resolver role
This role configures `kresd` to provide a network (per default only localhost) with a DNSSEC-validating, caching resolver.

WARNING: This role assumes that if you use Debian 8, you have backports enabled! It will also override '/etc/resolv.conf', so take care if you want to use this on a non-server system.

# Graylog-OPNsense_Extractors

Extractors for Graylog to parse OPNsense firewall logs. Should be able to parse most all IPv4 and IPv6 messages.
Fork of the original by [IRQ10](https://github.com/IRQ10/Graylog-OPNsense_Extractors)

## Updates

* 2021-06-17: Forked and updated to support OPNsense 21.1.7 message format (["filter: link rule hash to origin"](https://github.com/opnsense/core/commit/6452a8b321f7009439b545c03b163327cdc01464))
* 2021-02-07: Update to support OPNsense 21.1 message format (by [@knipp](https://github.com/Alphakilo/Graylog-OPNsense_Extractors/commit/45dae7fd8a607918983f49257ee93e7b7891aa3f))
* 2019-08-13: Update to support OPNsense message format change.
* 2018-06-21: Update to IPv6 ICMP. OPNsense sends "ICMPv6", remove case insensitive regex for better processing when under heavy load.

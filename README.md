# Russian government agencies and their associated network blacklists.

> [!IMPORTANT]
> A very important feature has been added: dedicated lists of VK/Max/OK Service networks that can be used to block **OUTGOING** traffic from your server (iptables/ipset and nftables formats are available).
> This can help reduce the risk of Messenger MAX being used to compromise your VPN server.
> The best security option is to avoid installing Messenger MAX at all on a phone where VPN access is configured.

**→ [https://github.com/C24Be/AS_Network_List](https://github.com/C24Be/AS_Network_List)**

**Ready-to-use blacklists in multiple formats (updated daily):**

- [Text blacklists in `blacklists/`](https://github.com/C24Be/AS_Network_List/tree/main/blacklists) - Plain text format with IPv4/IPv6 separation
- [Nginx configurations in `blacklists_nginx/`](https://github.com/C24Be/AS_Network_List/tree/main/blacklists_nginx) - Ready to include in your nginx config
- [IPTables/IPSet files in `blacklists_iptables/`](https://github.com/C24Be/AS_Network_List/tree/main/blacklists_iptables) - Optimized for iptables with ipset
- [nftables files in `blacklists_nftables/`](https://github.com/C24Be/AS_Network_List/tree/main/blacklists_nftables) - Ready-to-load sets and rules for nftables
- [Linux route files in `blacklists_route/`](https://github.com/C24Be/AS_Network_List/tree/main/blacklists_route) - VK route blackholes to loopback (IPv4/IPv6)

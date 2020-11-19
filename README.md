# mullvad config files

A simple set of scripts and a runit service for using
[Mullvad](https://www.mullvad.net) easily. These can be used to switch servers
with no hassle, or to ensure that the you connect to the VPN on boot.

For it to work, you need to have at least one Mullvad configuration file in
`/etc/wireguard`. The files can be generated
[online](https://mullvad.net/en/account/#/wireguard-config/).

The secondary script `mullvbest` uses a simple heuristic to pick a good server
from all those stored in `/etc/wireguard`.

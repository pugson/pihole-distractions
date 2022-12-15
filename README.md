# pihole-distractions
List of sites to block in Pi-hole when you’re trying to get some work done.

Pi-hole's latest GUI for managing domains is a clusterfuck once you have more than a dozen entries there. This list simplifies the process of enabling/disabling a batch of domains to block in a single press of a button on demand.

## Recommended use
1. Make a group inside Pi-hole of devices that you want affected by this blocklist.
2. Add https://raw.githubusercontent.com/pugson/pihole-distractions/main/blocklist.txt to your `Adlists` and select the group you made. ⚠️ Unselect `Default` so you don’t block access on other devices for anyone else on your network.
3. Enable/disable this blocklist with the toggle switch inside Pi-hole’s `Adlists`.
4. (Optional) Create a cron job that enables/disables this blocklist on a set schedule using the Pi-hole API.
5. (Optional) Create a [Raycast](https://raycast.com), [Alfred](https://alfredapp.com), [xbar](https://github.com/matryer/xbar), etc. workflow to manually flip this switch without having to go hunting into Pi-hole’s GUI.

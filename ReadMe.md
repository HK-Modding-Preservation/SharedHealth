# SharedHealth

A HKMP addon that allows synchronization of healing and damage across teams.

# Setup
When the mod and its dependencies are installed, all players need to be in the same team. Players not in a team will
not have their health synced. The sharing works per team, so you can have multiple shared healthbars on the same server.

# Known Issues
Deaths can sometimes feel counterintuitive. When an UI is open (map, inventory, dialogue, pause menu, etc.), if damage
has been taken, all healing and damage onwards are queued. The damage (modified with the healing received during the time)
is applied once the UI is closed, preventing issues with receiving damage with certain UIs open.
If a death would have happened when the UI was open, it is applied once it is closed.

# Mikrotik-Traffic-Shaping
Welcome to the Mikrotik-Traffic-Shaping wiki! This is simple example script for mikrotik traffic shaping especially for manage and limiting youtube traffic.

Usage
Just copy script inside the .cfg files and paste it to mikrotik terminal

If you want to use all the script the sequence is :
1. Youtube Firewall Mangle.cfg
2. Parent Queue Make things way more manageable.cfg
3. DHCP Script.cfg

The Youtube Firewall Mangle.cfg can be used standalone

if you want to just use the queue script without parent queue, just delete this line of script " parent=TrafficShaping" inside DHCP Script.cfg file

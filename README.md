# Boxes

## Vagrant Boxes for Rails Camp

These recipes are (very slightly) tailored to our specific equipment at Rails Camp.
RubyNZ owns a Mac Mini which is used as the VM host for these machines.
We have its Ethernet interface configured manually to `10.0.0.1/16` and each of these VMs is bridged onto that network.

One of our Airport Extremes is configured as the "core" and our Mac Mini, and other Airport devices are connected to that via ethernet.
All Airport devices are configured in straight bridge mode.
We use a WPA/WPA2 network with SSID `railscamp` and key `railscamp`.

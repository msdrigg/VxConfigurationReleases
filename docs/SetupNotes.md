# Setup process

## Server Setup

-   Setup EC2 Server
    -   Get Hostname
    -   Get SSH Keys and IP Address
    -   Ensure ports 5000 and 8833 are open on it
-   Get Vx Installed
    -   Get https setup for Vx
    -   Get UI Installed
    -   Get ServerApp installed
-   Get RTLS Installed
    -   `locrate.deb` and `install_deb.sh`
    -   Add `hostname` to server cert alternate name
-   Connect EX to RTLS and VX (Optional)
-   Setup the configuration excel and the layout map
    -   Need mac address from gateways and devices
    -   Need to know where gateways will be placed
    -   Need the map of the facility

## Device Setup

-   Sideload apk
-   Get Hostname, Wifi SSID, Wifi Password entered into the application (wifi ssid and password are for the network that the gateway will be finally connected to in facility)
-   Turn on devices, scan for devices and configure
-   WIFI scan issues
-   WIFI enable connect (don't cancel)
-   BeaconSet+ troubleshooting
-   Direct plugin troubleshooting (for G1's and Cassias)
-   Check hostname troubleshooting
-   Add testing step
    -   Need to add status page which shows which gateways have captured which packets in the last minute (iBeacon, TLM, iSmarch, ...)
    -   Need to add status page which shows which devices have broadcast which packets in the last minute (iBeacon, TLM, iSmarch, ...)
    -   Need to add status page which shows which devices have pinged which gateways in the last minute and their rssi's

## Troubleshooting

-   Need BeaconSet+ for troubleshooting and need teamviewer access to local computer for troubleshooting
-   Need angry ip for scanning for devices (and notice set url for mg3 gateway troubleshooting)
-   Ensure the url is reachable from network (why not??)

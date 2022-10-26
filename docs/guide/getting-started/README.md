---
sidebarDepth: 1
next: ../installation/
---

# Getting started

## About

SLZB-06 is a Zigbee adapter, that enables Zigbee packet forwarding over Ethernet, WiFi or Serial (USB) connection, and serves as an access point in a Zigbee network. The Zigbee adapter allows you to connect devices from different producers (Tuya, IKEA, Xiaomi, Gledopto, Moes, Sonoff and others) into one system. In order to properly use SLZB-06 you need to have an instance of [Home Assistant](https://www.home-assistant.io/installation/) and [zigbee2mqtt](https://www.zigbee2mqtt.io/guide/installation/).

### What is in the box?
- 1x SLZB-06 Zigbee Ethernet PoE USB WiFi Adapter
- 1x 5dB Antenna
- 1x microUSB-to-typeC adapter (just in case you want to use the USB connection but do not have a type-C cable)
- 2x adhesive tapes - if you want to surface mount your adapter - easiest way to do that
- 2x screws - if you want to mount your adapter using screws - easy, they are included
- 1x screwdriver (allen key) - you will use it to fix by screws;
- 1x mounting-template with QR code for manual - making screw mounting even easier and a QR code linking to this manual;
<img src="../../images/about/package.png" title="SLZB-06 About - Package" class="float-left" />  

## Powering the device
Device can be powered by either PoE through Ethernet cable or by type-C plug.

::: tip
Package contains microUSB-typeC adapter. If you want to power your device by type-C but do not have type-C cable, use the microUSB-typeC adapter.
:::

::: tip
SLZB-06 has optoelectronic isolation, so can be connected to the USB port of your PC and to Ethernet/PoE cable at the same time!
:::

## LED behaviour
- **<span style="color:yellow">Yellow</span>** LED is the power LED. Default operation: On when the unit is connected to a power source.
- **<span style="color:blue">Blue</span>** LED is the operation mode LED. Default operation: On when the device is in Zigbee-to-USB mode and off when the device is in Zigbee-to-Ethernet mode.
- **<span style="color:green">Green</span>** LED - Zigbee2MQTT connection LED. Default operation: On when Zigbee2MQTT has successfully connected to the device and Zigbee network is established. 
- **<span style="color:red">Red</span>** LED - reserved for further development with Zigbee2MQTT
<img src="../../images/about/leds-on-case.png" title="SLZB-06 About - Leds on case" class="float-left" />  

## Mount to wall

SLZB-06 adapter can be mounted to a wall, or any other surface you want, with either double-sided adhesive tape or screws. Both are included in the package.  
See the 6-step graphic instructions below for attaching the SLZB-06 adapter to double-sided adhesive tape and screws.

### Adhesive tape

<img src="../../images/about/ahvesive-first-row.png" title="SLZB-06 About - Adhesive 1" class="float-left" />

<img src="../../images/about/ahvesive-second-row.png" title="SLZB-06 About - Adhesive 2" class="float-left" />

### Screws

<img src="../../images/about/screws-first.png" title="SLZB-06 About - Screws 1" class="float-left" />

<img src="../../images/about/screws-second.png" title="SLZB-06 About - Screws 2" class="float-left" />  
<br>  

::: tip
Screwdriver (allen key) included in the package
:::

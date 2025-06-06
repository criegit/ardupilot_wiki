.. _common-telemetry-landingpage:
[copywiki destination="plane,copter,rover,blimp,sub"]
========================
Telemetry (landing page)
========================

Copter/Plane/Rover/Blimp support sharing information with a ground station (or
transmitter) using telemetry. Follow the links below for configuration
information based upon your set-up.

.. note:: Some RC systems incorporate telemetry in addition to RC control
.. note:: most pure telemetry radios connect to the autopilot via a serial UART using MAVLink 1 or 2 protocol. See :ref:`common-telemetry-port-setup`
.. note:: ArduPilot will automatically fall back to MAVLink1 if MAVLink 2 serial port protocol is selected and no MAVLink 2 data is received from the groundstation in response in fimware versions before 4.2, but not after
.. image:: ../../../images/Telemetry_LandingImage.jpg
    :target: ../_images/Telemetry_LandingImage.jpg

.. note:: High value systems using RC control over a telemetry link should consider :ref:`common-redundant-telemetry`

Short Range (<10KM)
===================

.. toctree::
    :maxdepth: 1

    Bluetooth <common-mission-planner-bluetooth-connectivity>
    CUAV PW-Link <common-cuav-pwlink>
    ESP8266 wifi telemetry <common-esp8266-telemetry>
    ESP32 wifi telemetry <common-esp32-telemetry>
    FrSky telemetry <common-frsky-telemetry>
    i-BUS telemetry <common-ibus-telemetry>
    Yaapu Bi-Directional Telemetry GCS <common-yaapu-gcs>
    HOTT telemetry <common-hott-telemetry>
    MSP (version 4.2) <common-msp-overview-4.2>
    SiK Radio v1 <common-3dr-radio-v1>
    SiK Radio v2 <common-sik-telemetry-radio>
    SiK Radio configuration <common-configuring-a-telemetry-radio-using-mission-planner>
    SiK Radio advanced configuration <common-3dr-radio-advanced-configuration-and-technical-information>
    XBee <common-telemetry-xbee>

Long Range
==========

.. toctree::
    :maxdepth: 1

    Andruav Android Cellular <https://cloud.ardupilot.org/andruav-index.html>
    Blicube RLINK P900 <common-blicube-rlink>
    ClearSky Airlink 4G LTE Telemetry <common-airlink-telemetry>
    CRSF/ELRS Telemetry <common-crsf-telemetry>
    CUAV P8 Radio <common-cuav-p8>
    CUAV P9 Radio <common-cuav-p9>
    DragonLink <common-dragonlink-rc>
    Herelink <common-herelink>
    Holybro 900Mhz XBP9X Telemetry Radio <https://shop.holybro.com/xbp9x-radio_p1268.html>
    Holybro Microhard Radio Telemetry Radio (P900/P840/P400-C1S) <https://holybro.com/products/microhard-radio>
    LTM telemetry <common-ltm-telemetry>
    mLRS <common-mlrs-rc.rst>
    RFD900 <common-rfd900>
    Rockblock Satellite Modem <common-telemetry-rockblock>
    SPL Satellite Telemetry <https://discuss.ardupilot.org/t/stretching-comm-links-from-indoors-to-the-globe/45896>
    UAVCast 3G/4G Cellular <common-uavcast-telemetry>
    XBStation 4G LTE Link <common-xbstation-telemetry>

Applications and Info
=====================

.. toctree::
    :maxdepth: 1

    FlightDeck FrSky Transmitter App <common-frsky-flightdeck>
    MAVLink2 Packet Signing (Security) <common-MAVLink2-signing>
    MAVLink High Latency Protocol <common-MAVLink-high-latency>
    Repeater for Wireless Ground Station Connections <common-wireless-gcs-repeater>
    Telemetry Radio Regional Regulations <common-telemetry-radio-regional-regulations>

-  :ref:`Yaapu Telemetry Scripts for OpenTX <common-frsky-yaapu>`


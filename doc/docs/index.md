# RSSI Viewer app

The RSSI Viewer app is a cross-platform tool that shows dBm per frequency in the 2.4 GHz range. It scans the 2400-2480 MHz range, records signal level on the Bluetooth® Low Energy channel frequencies, and presents the results.

You can use the tool with a sniffer device to look for interferers, check how channels are used, and to tweak settings like sweep delay and animation duration.

The RSSI Viewer app is installed and updated using [nRF Connect for Desktop](https://docs.nordicsemi.com/bundle/nrf-connect-desktop/page/index.html).

## Installing the RSSI Viewer app

For installation instructions, see [Installing nRF Connect for Desktop apps](https://docs.nordicsemi.com/bundle/nrf-connect-desktop/page/installing_apps.html) in the nRF Connect for Desktop documentation.

!!! note "Note"
    {{legacy_driver_note}}

## Supported devices

You can use the following Nordic Semiconductor devices as the sniffer with the RSSI Viewer app:

- nRF52 DK (PCA10040)
- nRF52840 DK (PCA10056)
- nRF52840 Dongle (PCA10059)

When you [select the device](overview.md#select-device), the tool will reprogram the connected board to act as the sniffer.

!!! note "Note"
    {{legacy_driver_note}}

## Application source code

The code of the application is open source and [available on GitHub](https://github.com/NordicSemiconductor/pc-nrfconnect-rssi).
Feel free to fork the repository and clone it for secondary development or feature contributions.

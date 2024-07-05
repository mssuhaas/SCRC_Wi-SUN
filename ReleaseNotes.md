# Release Notes (05th July 2024)
## What's New:

* **CoAP over IPv6:** Firmware now uses CoAP protocol over IPv6 (UDP) to control relays and fetch node details from the border router. This improves communication efficiency compared to traditional methods.
* **Updated SDKs:** The firmware uses the latest GSDK (GreenSpin SDK) v4.4.3 and SiSDK (Silicon Labs SDK) v2024.6.0 for improved functionality and security.

## New Changes (Updates):

* **Node Details:** Added fields to retrieve additional node information:
    * **IPv6 Tag:** Added an IPv6 tag to the `/om2m` route, allowing retrieval of a node's specific IPv6 address.
    * **Parent:** Retrieves the parent node's address.
    * **Running:** Provides the uptime of the node since power-on.
    * **Connected:** Shows the time since the node connected to the border router.
* **Status LEDs:** Added LEDs to indicate the node's connection status to the border router (connected/disconnected).

## Known Issues:

- None
# Downlinks from the LoRaWAN network

## **Goal**
Write an application that prints a message when it receives a downlink
 from the LoRaWAN network

## Instructions
  - Reuse ~/riot-course-exercises/riot-lorawan/lpp` to make LED1 blink
    when receiving a message from the LoRaWAN network.
  - Send downlink messages to your node from the TTN network: go to
    `Devices> [your_device] > Downlinks`
  - **Optional**: Use the TTN MQTT broker to send and receive data from
    your node. Check the appendix below.

## Appendix: Using the MQTT API
  - Follow the MQTT quick start in TTN at
    `https://www.thethingsnetwork.org/docs/applications/mqtt/quick-start.html`
  - Publish data to your node and subscribe for uplink messages

_TIP_: base64 payload can be decoded with the command `$ base64 -d <<< dGVzdA==`
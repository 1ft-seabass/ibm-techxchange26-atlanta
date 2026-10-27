# Introduction & Today's Architecture

## Source code

![Screenshot of the public GitHub repository for today's source code](image-4.png)

Source code of today's architecture: https://github.com/1ft-seabass/ibm-bob-codeengine-techxchange26-atlanta

## Architecture

![Diagram step 1: a person with a laptop, "I made with IBM Bob!"](image-1.png)

I made this with IBM Bob for my tech prototyping.

![Diagram step 2: a Babylon.js cube running on IBM Cloud Code Engine, tapped from the laptop](image-2.png)

This is a Hono + Vue + Bootstrap + Babylon.js system running on IBM Cloud Code Engine.

![Diagram step 3: the tap sends an MQTT message to the IoT devices, a LEGO light and servo](2026-10-25-00-36-07-851.jpg)

When the Babylon.js cube is tapped, it controls an IoT light and an IoT servo with MQTT.

## How it works

- A Babylon.js cube UI makes an MQTT signal when tapped.
- IoT devices (a light and a servo) act when they receive the MQTT signal.

## Who does what

- Me
  - Sharing prototype-making knowledge and context with Bob.
- IBM Bob
  - Deploy flow (ibmcloud CLI)
  - Web backend + frontend
  - IoT MQTT protocol handling
  - Babylon.js 3D UI making

## Next

I want to build this kind of collaboration prototype for client work!
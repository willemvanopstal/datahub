---
schema: default
title: AHN2 WMS
organization: PDOK
notes: "ahn wms services</br>\r\nYou should read the capabilities to specifiy the actual layer."
resources:
  - name: 0.5m interpolated
    url: >-
      https://geodata.nationaalgeoregister.nl/ahn2/wms?&request=GetCapabilities&service=WMS
    format: WMS
  - name: 0.5m non-interpolated
    url: >-
      https://geodata.nationaalgeoregister.nl/ahn2/wms?&request=GetCapabilities&service=WMS
    format: WMS
  - name: 0.5m raw
    url: >-
      https://geodata.nationaalgeoregister.nl/ahn2/wms?&request=GetCapabilities&service=WMS
    format: WMS
  - name: 5m
    url: >-
      https://geodata.nationaalgeoregister.nl/ahn2/wms?&request=GetCapabilities&service=WMS
    format: WMS
  - name: grid index
    url: >-
      https://geodata.nationaalgeoregister.nl/ahn2/wms?&request=GetCapabilities&service=WMS
    format: WMS
license: 'https://creativecommons.org/publicdomain/zero/1.0/'
category:
  - Elevation
  - WMS / WFS
---
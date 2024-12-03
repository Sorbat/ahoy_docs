AhoyDTU Dokumentation
===================================

**AhoyDTU** ist ein Projekt um Wechselrichter der Marke Hoymiles mit eigener Hardware auszulesen. Es basiert im wesentlichen aus einem ESP und einem Funkmodul. 

Wenn es in Ihren finanziellen Möglichkeiten liegt und Sie keinen großen Wert darauflegen, die DTU von Grund auf neu zusammenzubauen, sollten Sie sich für das `OpenDTU Fusion<https://opendtu-onbattery.net/3rd_party/opendtu_fusion/>`_ entscheiden. Es integriert beide Arten von HF-Modulen zusammen mit einem der leistungsstärkeren unterstützten Mikrocontroller auf einem einzigen gebrauchsfertigen Board. `Das OpenDTU Fusion kann hier erworben werden.<https://shop.allianceapps.io/products/allianceapps-opendtu-fusion/>`_

Das OpenDTU Fusion wurde durch die Community entwickelt und wird von einer großen Community unterstützt. Dies ermöglicht einen schnellen Austausch und Hilfestellung.

Die Vergangenheit zeigte immer wieder, dass es bei selbstgebauten DTUs zu Problemen kommen kann, welche eine zeitaufwändige und komplexe Fehlersuche und -behebung erfordern. Zudem sind Steckverbindung mit Jumperkabeln bzw. Dupontsteckern nicht für einen dauerhaft zuverlässigen Betrieb geeignet. 

Die DTU macht den Wechselrichter auch per MqTT erreichbar. Ahoy stellt neben den aktuellen Produktionsdaten zudem die Möglichkeit der Ansteuerung des Wechselrichters bereit. Damit lässt sich der Wechselrichter zum Beispiel in seiner Leistung begrenzen.

Das Projekt ist Open Source und wird unter einer CC-BY-NC-SA 4.0 Lizenz auf `Github <https://github.com/lumapu/ahoy>`_ veröffentlicht. Das Projekt hat auch eine `Website <https://ahoydtu.de>`_, die einen Online-Installer enthält. Die `aktuelle Firmware <https://fw.ahoydtu.de>`_ ist ohne Login jederzeit in verschiedenen Verisonen verfügbar.

.. note::

   Dieses Projekt ist noch im Entwicklungsstadium

**Warning: HMS-XXXXW-2T WiFi inverters are not supported. They have a 'W' in their name and a DTU serial number on its sticker**

**Achtung Vorsicht: HMS-XXXXW-2T WiFi Wechselrichter werden nicht unterstützt. Sie haben ein 'W' im Modellnamen und eine DTU-Seriennummer auf dem Aufkleber.**

Inhalte
--------

.. toctree::

   usage
   mqtt
   api
   faq
   protocol
   zeroExport

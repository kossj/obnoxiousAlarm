# obnoxiousAlarm
🎤 ⏰ 🚀
An obnoxious alarm powered by a car horn, and a good excuse to tinker with IOT.

## What does it do?

When an Alexa alarm goes off, an IFTT integration puts a 1 on an Adafruit IO feed.
When the alarm is dismissed either via Alexa or button on alarm, a O is sent to the Adafruit feed.

## Running it yourself

1. Create a feed on [io.adafruit.com](io.adafruit.com) called ```car_alarm_on```, and turn history off.
2. Use [ITTT](https://ifttt.com) to connect the [Activate](https://ifttt.com/applets/hdNCZnLK-if-your-alarm-goes-off-then-send-data-to-car_alarm_on-feed) and [Deactivate](https://ifttt.com/applets/hCLstQmP-if-you-say-alexa-trigger-deactivate-car-alarm-then-send-data-to-car_alarm_on-feed) applets to your Adafruit account. Read through the details, these simply write a 1 or a 0 to the Adafruit IO feed when an Alexa alarm goes On or Off.
3. Deploy the arduino code to you IOT enabled Arduino.

## Resources used:
- [Board Docs](https://docs.arduino.cc/hardware/mkr-wifi-1010)
- [Adafruit IO Docs](https://io.adafruit.com/api/docs)
- [Code from this example listed on the MKR WiFi 1010 Arduino store page](https://github.com/avilmaru/enchufe_inteligente_wifi)

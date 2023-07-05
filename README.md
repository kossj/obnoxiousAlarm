# obnoxiousAlarm
🎤 ⏰ 🚀
An obnoxious alarm powered by a car horn, and a good excuse to tinker with IOT.

## Why (does this exist)?

I was contacted with a proposition to trigger a very obnoxious alarm, made with a car horn, with an Alexa.

## What (is in the repo)?
*these are all currently guesses.*
A basic skill, which is linked to an Alexa routine that is triggered when an alarm goes off. This skill will then, turn the relay of the alarm on, which will be controlled with an Arduino IOT board, likely the [MKR WIFI 1010](https://docs.arduino.cc/hardware/mkr-wifi-1010).

The logic flow will look like this:
1. Alexa alarm goes off
2. Routine is called, alarm clock skill goes off
3. Skill activates relay on arduino
4. Closing the circut activates the alarm
5. Pressing a button on the clock deactivates the alarm

## Resources used:
*this is an abriged list*
- [Board Docs](https://docs.arduino.cc/hardware/mkr-wifi-1010)
- [Alexa Skills SDK Docs](https://developer.amazon.com/en-US/alexa/alexa-skills-kit/get-deeper/sdk)
- [This hackster.io project](https://github.com/xelfer/nicksclock)

## Contributing
Submit a pull request! 

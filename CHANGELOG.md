0.9.5 / 2018-03-06
==================

  * fix multiservices accessories, getService by subtype

0.9.4 / 2018-03-06
==================

  * WARNING - possibly breaking change. See Readme
  * remove obsolete services
  * set service subtype (fix [#89](https://github.com/hobbyquaker/homekit2mqtt/issues/89))
  * hand over service index for subtype (prepare [#89](https://github.com/hobbyquaker/homekit2mqtt/issues/89))
  * save attr in mqttCallbacks (prepare [#67](https://github.com/hobbyquaker/homekit2mqtt/issues/67))
  * cleanup accessory uuid log
  * log setupURI
  * show QR code on start (closes [#88](https://github.com/hobbyquaker/homekit2mqtt/issues/88))

0.9.3 / 2018-02-19
==================

  * RGB topics for LightBulb (closes [#78](https://github.com/hobbyquaker/homekit2mqtt/issues/78))

0.9.2 / 2018-02-18
==================

  * implement identify (closes [#83](https://github.com/hobbyquaker/homekit2mqtt/issues/83))
  * send empty string for undefined payloads
  * add command line option --insecure (closes [#85](https://github.com/hobbyquaker/homekit2mqtt/issues/85))
  * improve documentation
  * changelog
  * exclude docs
  * prepare identify config ([#83](https://github.com/hobbyquaker/homekit2mqtt/issues/83))
  * fix type selector
  * new config schema

0.9.1 / 2018-02-17
==================

  * remove alert
  * fix add/stop button
  * fix default 0
  * wait on quit
  * dont subscribe empty topics
  * log error when trying to subscribe empty topic
  * remove identify
  * increase button col width

0.9.0 / 2018-02-17
==================

  * batteryLevel conversion (closes [#82](https://github.com/hobbyquaker/homekit2mqtt/issues/82))
  * multi-service accessories
  * extend test config

0.8.4 / 2018-02-16
==================

  * move test-config
  * convert identify topic/payload, prepare saving of converted config
  * fix [#80](https://github.com/hobbyquaker/homekit2mqtt/issues/80)
  * parseInt config variables

0.8.3 / 2018-02-14
==================

  * edit properties (close [#62](https://github.com/hobbyquaker/homekit2mqtt/issues/62))
  * add props
  * add hue templates
  * fix testbridge command

0.8.2 / 2018-02-14
==================

  * add testbridge command

0.8.1 / 2018-02-14
==================

  * set props TargetHeatingCoolingState

0.8.0 / 2018-02-14
==================

  * enable props for TargetHeatingCoolingState
  * alphabetic order
  * reformat
  * add Faucet, IrrigationSystem, Microphone, Slat, Valve
  * test BatteryService
  * fix test
  * fix accessory id
  * always set names
  * Revert "fix logging"
    This reverts commit 0e1d104
  * fix logging
  * add service name ([#56](https://github.com/hobbyquaker/homekit2mqtt/issues/56))
  * adapt new config schema ([#56](https://github.com/hobbyquaker/homekit2mqtt/issues/56))
  * rename dir accessories to services (prepare [#56](https://github.com/hobbyquaker/homekit2mqtt/issues/56))
  * refactor accessory creation (prepare [#56](https://github.com/hobbyquaker/homekit2mqtt/issues/56))

0.7.10 / 2018-02-12
===================

  * remove unnecessary param
  * unifiy mqtt logging
  * fix slat
  * fix return
  * implements BatteryService (closes [#76](https://github.com/hobbyquaker/homekit2mqtt/issues/76))
  * fix log output
  * unify config names
  * add TemperatureDisplayUnits config
  * implements slat (closes [#74](https://github.com/hobbyquaker/homekit2mqtt/issues/74))
  * remove StatefulProgrammableSwitch (close [#75](https://github.com/hobbyquaker/homekit2mqtt/issues/75))

0.7.9 / 2018-02-11
==================

  * use val (close [#57](https://github.com/hobbyquaker/homekit2mqtt/issues/57))

0.7.8 / 2018-02-11
==================

  * implement valve and irrigation
  * implement config
  * prepare new services
  * implement faucet [#41](https://github.com/hobbyquaker/homekit2mqtt/issues/41)

0.7.7 / 2018-02-09
==================

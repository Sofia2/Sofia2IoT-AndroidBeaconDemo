# Sofia2IoT-AndroidBeaconDemo
Simple PoC app to show Sofia2 IoT capabilities.

###### Testing and Demo

You may find a ready to use APK. In order to install the app you must allow installation of apps from unknown sources, to do so just go to Settings->Security->Device administrators-> and enable "Allow installation of apps from unknown sources".
This app is built to demonstrate a typical IoT scenario so it will ask you for some permissions.

This example connects your phone to Sofia2 IoT Platform. Please check your 'Settings' within the app to assure you have properly set Ontology name, ThinKP name and its token. Also you must configure the e-mail address to be notified when the Beacon is detected by the app.

On the main screen, you can tap "Play" on the Toolbar to initiate a service fetching accelerometer data, performing a BLE scanner to detect our beacon, and sending all this data to Sofia2. The action is finished whenever you tap "Stop" or when the beacon is detected within short-range.

###### Development

Clone or download the App to start. There are few TODOs in the code highlighting some suggested improvements (for instance including your phone's IMEI code within the frame). Please remember to update your ontologies' definition on Sofia2.com with any changes you perform in the app (also marked as a TODO).

If you need support from us, please feel free to contact us at plataformasofia2@indra.es or at www.sofia2.com. 

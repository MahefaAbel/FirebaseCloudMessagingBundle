
# FirebaseCloudMessagingBundle

Ceci est une version ameliorer du [https://github.com/fre5h/FirebaseCloudMessagingBundle](https://github.com/fre5h/FirebaseCloudMessagingBundle).

Provides integration with Firebase Cloud Messaging API in Symfony applications.

Supported client platforms:

* [x] Android
* [x] iOS
* [x] Web browser

# Installation
Pour installer le bundle, excecuter la command suivant :
`composer require MahefaAbel/firebase-cloud-messaging-bundle`

# Configuration
Les configuration suivant est à mettre dans `config.yml`

    mahefa_firebase_cloud_messaging:
	    sender_id : test
	    server_key : AIzaSyZ-1u...0GBYzPu7Udno5aA
	    endpoint : https://fcm.googleapis.com/fcm/send
	    guzzle_timeout : 120


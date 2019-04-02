
# FirebaseCloudMessagingBundle

Ceci est une version ameliorer du [https://github.com/fre5h/FirebaseCloudMessagingBundle](https://github.com/fre5h/FirebaseCloudMessagingBundle).

Provides integration with Firebase Cloud Messaging API in Symfony applications.

Supported client platforms:

* Android
* iOS
* Web browser

# Installation
`composer require MahefaAbel/firebase-cloud-messaging-bundle`

# Configuration
Les configuration suivant est à mettre dans `config.yml`

    fresh_firebase_cloud_messaging:
	    sender_id : test
	    server_key : AIzaSyZ-1u...0GBYzPu7Udno5aA
	    endpoint : https://fcm.googleapis.com/fcm/send
	    guzzle_timeout : 120


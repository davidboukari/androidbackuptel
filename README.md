# androidbackuptel

## Full backup & restaure with adb
```
apt install adb
adb start-server

# Backup
adb backup -apk -shared -all -f backup-file.adb

# Restore
adb restore backup-file.abb
```


## backup and restaure contact

* http://www.prodigemobile.com/tutoriel/transferer-contact-android/

```bash
Importer les contacts stockés sur un vieux téléphone

Le bon vieux carnet d’adresses papier fait désormais partie du passé. Nous vivons aujourd’hui dans une société numérique. La grande majorité des gens stocke les coordonnées de leurs contacts sur un téléphone portable. C’est certes plus pratique mais quand on souhaite changer de smartphone, cela peut poser quelques problèmes surtout quand on ne maîtrise pas très bien toutes les subtilités d’Android.
Transférer son carnet d’adresses via votre compte Google

En tant qu’utilisateur Android vous disposez d’un compte Google et donc d’une adresse Gmail. Le service de messagerie gratuit édité par Google propose une fonctionnalité permettant de synchroniser ses contacts téléphoniques. Pour l’utiliser, il vous suffit juste de vérifier que celui-ci est bien activé sur votre appareil.

    Ouvrez les paramètres de votre ancien téléphone
    Dans la rubrique Comptes, cliquez ensuite sur l’icône Google puis sur votre adresse e-mail
    Vérifiez bien que la case Contacts est bien cochée
    Sinon faîtes le tout de suite
    La synchronisation va alors se lancer automatiquement
```

## Backup whatsapp discussions

* https://faq.whatsapp.com/en/android/28000019/

```bash
How to back up to Google Drive

The easiest way to transfer your WhatsApp data to a new phone is by using Google Drive. We recommend connecting your phone to Wi-Fi prior to backing up your chats to Google Drive, as backup files can vary in size and consume mobile data, causing additional charges.
Requirements

In order to use Google Drive backup, you need to have:

    A Google account activated on your phone.
    Google Play services installed on your phone.
    Enough free space on your phone to create the backup.
    A strong and stable Internet connection.


```


## Restaure whatsapp discussions

* https://faq.whatsapp.com/en/android/20887921/

```bash
Restore from a Google Drive backup

In order to successfully restore a Google Drive backup, you need to use the same phone number and Google account used to create the backup.

To restore your backup:

    Uninstall and reinstall WhatsApp.
    Open WhatsApp and verify your number.
    When prompted, tap RESTORE to restore your chats and media from Google Drive.
    After the restoration process is complete, tap NEXT. Your chats will be displayed once initialization is complete.
    WhatsApp will begin restoring your media files after your chats are restored.

Note: If you install WhatsApp without any prior backups from Google Drive, WhatsApp will automatically restore from your local backup file.
```


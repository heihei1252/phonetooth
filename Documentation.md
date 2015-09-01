# Introduction #
Phonetooth is an application written in python that allows you to send text messages and files using your mobile phone through a bluetooth connection.
Phonetooth is designed with ease of use in mind. No difficult setup is necessary. You can scan for paired devices in the pereference dialog and select the phone you wish to use.


# Connection methods #
As of version 0.3.0 Phonetooth can use 3 connection methods: bluetooth, serial device and the gammu connection method.

The bluetooth connection method allows you to scan for a bluetooth device which will be used for the communication. This method uses AT-Commands to communicate with the phone, if your phone supports AT-commands and has bluetooth then this is the recommended method.

The serial device method allows you the specify the location of a serial device that will be used for the communication (e.g /dev/rfcomm0). This method also uses AT-Commands to communicate with the phone.

If your phone does not support AT-commands but is supported by gammu (check: http://www.gammu.org/wiki/index.php?title=Phones:Support) you can use the gammu connection method. Phonetooth will then use gammu to communcate with the phone, thus  a valid ~/.gammurc file must be present for the communication to work. In the preference dialog you can specify which device from the ~/.gammurc file will be used by providing the index in the file.

# Dependencies #
  * pygtk
  * pybluez
  * pyserial
  * dbus-python
  * obex-data-server
  * python-gammu (only if you want to use the gammu back end)

# Installation #
Unpack the source archive.
Run
```
./configure --prefix=/usr
```
where prefix is the same prefix as used for the python installation.
Then run
```
make install
```
as root.

You can now launch the application by running phonetoothui from the command line or by clicking it in the application menu.
PhoneTooth is an application written in python that allows you to send text message using your mobile phone through a bluetooth connection. It also allows you to manage the files on your mobile phone.

## News ##
### August 20, 2008 ###
Release 0.5.1
  * Fix crash when certain icons where not found in the icon theme

### August 05, 2008 ###
Release 0.5.0
  * Phone browser added. Files on the phone can be browsed and copied using drag & drop.

### June 03, 2008 ###
Release 0.4.1
  * Restored compatibility with python 2.4

### May 30, 2008 ###
Release 0.4.0
  * Improved device discovery, takes less time
  * Improved file transfer with obex-data-server
  * Import contacts from file
  * Send message to multiple contacts
  * Scanning for devices no longer hangs when no bluetooth device is present
  * Option to store sent messages on the phone

### Mar 30, 2008 ###
Release 0.3.1
  * Made code work with python 2.4 (no longer requires 2.5)

### Mar 29, 2008 ###
Release 0.3.0
  * Allow connection through serial device
  * Contacts can be exported to csv
  * Support for unicode text messages
  * Support for multi-part messages
  * Delivery report option added
  * Auto-detect port for file transfer

### Mar 20, 2008 ###
Release 0.2.2
  * Fixed bug in UTF-8 detection

### Mar 19, 2008 ###
Release 0.2.1
  * gettext support
  * Dutch translations
  * Set UTF-8 character set on phone if available
  * Character count updates on paste and drag

### Mar 15, 2008 ###
Release 0.2.0
  * Support for sending messages in PDU mode (some devices don't support text mode)
  * Added python gammu as backend (should increase number of supported devices)
  * New config file layout

### Mar 09, 2008 ###
Release 0.1.2
  * Fixed bug in device selection dialog, bottom device was always selected

### Mar 09, 2008 ###
Release 0.1.1
  * Device discovery is less strict, should find more devices
> (~/.phonetooth directory must be deleted or application will crash)

### Mar 05, 2008 ###
Release 0.1.0
  * Initial release of phonetooth
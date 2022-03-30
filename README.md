
# iCloud Patched Installers for Windows Server

This repository stores a patched version of the iCloud Installer for Windows. The patch is very simple and allows iCloud to be installed on Windows Server (as it didn't work)


## How to use

To install iCloud:


##### • Uninstall any and all versions of iCloud, iTunes, Apple Software Update, Apple Application Support and Bonjour

##### • Download the repository in a ZIP or cloning it with Git

##### • Unzip but do not run the iCloud Patched installer yet, this is because we need to install all of the dependendices that the iCloud install needs

##### • Run AppleSoftwareUpdate.msi, Bonjour and AppleApplicationSupport.msi (pick the right installer for your system architechture)

##### • After all of these have been installed, run the patched iCloud installer and everything should run smoothly

##### You can choose to reinstall iTunes if you want.


## FAQ

#### Why would I need to run iCloud on Windows Server?

If you have a spare machine running Windows Server and you want to, for example: run AltStore auto refresh on it, you require iCloud to sync with the device over WiFi

#### Does AltStore work on Windows Server?

AltServer itself works perfectly fine on Windows Server but iTunes has an issue where iTunesHelper.exe (Windows Server issue) will crash on load which means an iDevice can not communicate with the Server which renders AltStore kinda useless.

#### Is this stable?

For now, it seems stable but I would not rely on it as a long term solution as Apple could release an iCloud update and bork the entire installation.

#### Does this have support?

Sorry, as this is a one time project and i've assembled it in one evening, I won't provide support as I don't see a point in doing so.
## License

iCloud and iTunes and all other related programs and materials are property of Apple Inc and not mine.


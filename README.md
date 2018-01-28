Using the Create React Native App to code smartphone gestures to direct the progression of a few short film clips.  Serves as a springboard for future work.


## Environment Setup

*Don't clone this repo yet!  Follow the subsequent setup instructions first.*

Install the [expo.io app](https://expo.io/learn) on your Android phone.

The Create React Native App is touchy about which versions of node/npm is used.  To avoid any confusion, we will be using a version manager to control our node/npm versions, specifically node 6.12.3 and npm 3.10.10.

### Windows
1. Uninstall any existing versions of node by both:
    1. Uninstalling node through the Control Panel (Add or Remove Programs)
    2. Deleting the existing npm install location, "C:\Users<user>\AppData\Roaming\npm"
2. Download, extract, and run "nvm-setup.zip" from Release 1.1.6 of nvm-windows.  [Download page.](https://github.com/coreybutler/nvm-windows/releases)
3. In terminal, `nvm list available`
4. `nvm install 6.12.3`
5. `nvm use 6.12.3`
6. Double check that you are using the correct versions:
    1. `node -v` should show v6.12.3
    2. `npm -v` should show 3.10.10
7. You may now clone this repo.

If your node/npm versions are incorrect, use [nvm-window's README](https://github.com/coreybutler/nvm-windows) to troubleshoot.

### mac/linux
1. Follow the nvm Git installation instructions [here](https://github.com/creationix/nvm#git-install).
2. In terminal, `nvm ls-remote`
3. `nvm install 6.12.3`
3. In a new terminal, `nvm use 6.12.3`
4. You may now clone this repo via the second terminal.

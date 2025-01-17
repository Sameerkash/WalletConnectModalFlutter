## 2.1.2

- Multiple UI improvements
- Added additional tests
- Wallet list is now displayed properly
- "Recent" wallet is now displayed based on the last used wallet
- Disabled `WalletConnectModalConnect` button if there is no requiredNamespaces set

## 2.1.1

- Some functions updated to be protected instead of private for easier inheritance

## 2.1.0

- Added `reconnectRelay` to the WalletConnectModalService to allow for manual reconnection to the relay
- Updated tests to reflect new changes

## 2.0.0

- Added setOptionalNamespaces to WalletConnectModalService
- Renamed setDefaultNamespaces to setRequiredNamespaces
- Network Error (Default connect button) now attempts to reconnect if you click on it

## 1.2.4

- Added small size constraint back to WalletConnectModalConnect button
- Added `sessionTopic` to launch wallet so that MetaMask will redirect back to dApp

## 1.2.3

- Removed size constraints on WalletConnectModalConnect button

## 1.2.2

- Updated to `walletconnect_flutter_v2` v2.1.3
- Bug fixes and code changes based on how network errors are handled now

## 1.2.1

- Updated to `walletconnect_flutter_v2` v2.1.1
- Internal updates to accomodate simple extensions to the modal
- Added network error handling when trying to connect to the relay and it fails
- `WalletConnectModalConnect` widget will now show `Network Error` when the relay fails to connect
- Tests added and updated

## 1.2.0

- Massive internal overhaul of how widgets are handled to allow extensibility
- Added `connectWallet` function to `IWalletConnectModalService` 
- Additional automated UI tests to ensure complete functionality of pages

## 1.1.7

- Added ability to inject services that need init into the modal, will be used by Web3Modal
- Bug fixes and polish

## 1.1.6

- Updated to `walletconnect_flutter_v2` v2.0.16

## 1.1.5

- Migrated to use widget stack instead of states for easier extension into Web3Modal
- Opened up modal service to allow for a start widget to be passed in
- Added WalletConnectModalServices class to cleanly expose all available services

## 1.1.4

- Modal now regenerates the WC URI when you tap on a wallet or open the QR Code
- Other minor bug fixes

## 1.1.3

- Updated to `walletconnect_flutter_v2` v2.0.15
- Additional tests to ensure robustness
- Example app updates

## 1.1.2

- Updated to `walletconnect_flutter_v2` v2.0.13
- UI Updates

## 1.1.1

- Updated the URL launching and added a full test suite
- UI updates to be more in line with official WalletConnect design
- Bug fixes

## 1.1.0

- WalletConnectModalTheme widget no longer required, the default theme is light mode, to override this a `WalletConnectModalTheme` widget must be used.
- Fixed issues with `wc://` deep links.
- Multiple bug fixes.
- Tests added for major paths of each widget and service.

## 1.0.0

- Initial release

Throwaway prototype host for the Polkadot App backup-key experiment:

- `.well-known/assetlinks.json`: App Links (`handle_all_urls`) and passkeys (`get_login_creds`) for `io.parity.polkadotapp.debug` (local dev keystore).
- `backup-key/`: static fallback page shown when the app isn't installed. No scripts, so the `#k=` fragment never leaves the browser.

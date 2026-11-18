# Together Privacy Policy

_Last updated: November 18, 2026_

Together ("the extension") lets two or more people browse and watch together: links, scrolling, cursors and video playback in one browser tab are mirrored in the other person's browser. This policy explains what data the extension handles and where it goes.

**Short version:** the developer does not collect, store, sell or have access to any of your data. There are no accounts, no analytics, no ads and no tracking. What you do in a synced tab is sent directly, encrypted, to the people in your room and nowhere else.

## 1. Data the developer collects

None. The extension has no servers of its own and sends nothing to the developer.

## 2. Data stored on your device

- **Your display name**, which you type in the popup, is saved in Chrome's local extension storage so you don't have to retype it.
- **The current room state** (room code, which tab is synced, connection status) is kept in Chrome's session storage and is erased when you close the browser.

You can erase this data at any time by removing the extension.

## 3. Data shared with the people in your room

Only while you are in a room, and only for the **one tab** you chose to sync, the extension sends the following directly to your partner's browser over an encrypted peer-to-peer WebRTC connection (DTLS):

- the address (URL) of the synced tab when it changes;
- your cursor position, clicks and scroll position on that page;
- text you type into ordinary fields on that page, such as search boxes and filters;
- video playback state: play, pause, current time and speed;
- your display name.

The extension **never** sends the contents of password fields, payment card fields, one-time codes or hidden fields. Other tabs are never synced. Pages, cookies, accounts and video streams are not shared: each browser loads the websites itself.

Only share a room code with people you trust. Anyone who joins your room sees what you do in the synced tab.

## 4. Third-party services used to connect

To let two browsers find each other on the internet, the extension uses these public services when a connection is set up:

- **PeerJS signaling server** (`0.peerjs.com`, run by the open-source PeerJS project). It relays the room identifier and the technical connection descriptions (which include network addresses such as IP addresses) between the browsers in a room. It does not receive what you browse.
- **STUN servers** run by Google (`stun.l.google.com`) and Cloudflare (`stun.cloudflare.com`). They tell your browser its public IP address so a direct connection can be made.

These services may see your IP address, as with any internet connection. Their own privacy policies apply, and the developer does not control or receive their logs.

## 5. How data is used

Data is used only to provide the extension's single purpose: keeping a tab in sync between the people in a room. It is not sold, not transferred to third parties for any other purpose, not used for advertising, and not used to determine creditworthiness or for lending.

## 6. Permissions

- **Access to websites**: needed to show your partner's cursor and to mirror clicks, scrolling and video playback on any site you choose to browse together.
- **tabs**: to follow the address of the synced tab and open the same page for your partner.
- **scripting**: to activate syncing in a tab that was already open before the extension was installed.
- **storage**: to remember your display name and the current room state.
- **offscreen**: to keep the peer-to-peer connection running in the background.

## 7. Children

The extension is not directed at children under 13 and does not knowingly handle their data.

## 8. Changes to this policy

If this policy changes, the updated version will be published at the same address with a new "Last updated" date.

## 9. Contact

Questions about privacy: [tutudun2@gmail.com](mailto:tutudun2@gmail.com)

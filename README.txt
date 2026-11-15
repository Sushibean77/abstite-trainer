ABSITE Trainer: home-screen app

Put every file in this folder at the root of any HTTPS static host, then open the address on your phone.

GitHub Pages (free):
1. github.com > New repository > name it (e.g. absite) > Public > Create.
2. "uploading an existing file" > drag in all files from this folder > Commit.
3. Settings > Pages > Source: Deploy from a branch > Branch: main, folder / (root) > Save.
4. After about a minute the app is at https://YOURNAME.github.io/absite/

Install:
- iPhone/iPad: open the address in Safari > Share > Add to Home Screen.
- Android: open in Chrome > menu > Install app (or Add to Home screen).

After the first load it works offline. Progress is stored on the device.
To bring progress over from the artifact: Stats > Progress and devices > Create code > Copy, then in the app Stats > paste > Import.

Updating: replace index.html, and change V in sw.js (absite-v1 to absite-v2) so phones pick up the new copy.

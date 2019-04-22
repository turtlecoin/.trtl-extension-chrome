# ![image](https://user-images.githubusercontent.com/34389545/56409412-8f1c4600-623e-11e9-961b-ed57382df370.png)

TRTL-DNS addon for Chrome lets you surf **.trtl**, and OpenNIC domains, and other OpenNIC peered domains.

-------

**Attention: Chrome requires `http://` prefix or a pathname**

If you type an address like `edu.trtl` into the address bar and hit Enter - you will be taken to Google search page. You have to type `http://edu.trtl` or add a slash at the end: `edu.trtl/`. See [this issue for details](https://github.com/B-DNS/Chrome/issues/2).

-------

TRTL-DNS is a public web resolver. It operates at https://dns.trtlnic.com (API description is coming soon).

For the list of OpenNIC support domain names see the [full list](https://wiki.opennic.org/opennic/dot).

--------

## Installing Debug Version

You can permanently load a debug (unsigned) extension into Chrome, i.e. it will survive restart.

**Disable existing TRTL-DNS extension, if installed, before installing its debug version!**

1. Open Extensions tab: click on the button with 3 dots, open _More tools_ submenu, then click on _Extensions_ item.
![Step 1](https://i.imgur.com/74xcLC7.png)

2. In the tab that has just opened, tick the checkbox named _Developer mode_, then click on _Load unpacked extension_ button that should have appeared.

![Step 2](https://i.imgur.com/WTQD9QD.png)

3. Select the extension's directory. The directory should contain all files from the [Chrome GitHub Repository](https://github.com/turtlecoin/.trtl-extension-chrome).

4. Once the open dialog is submitted, a new extension should appear in the Extensions tab.

![Step 4](https://i.imgur.com/i3humCn.png)

5. In a regular Chrome tab, navigate to a resource in question (e.g. `edu.trtl/`).

6. Enjoy surfing new **.trtl** domains!

## Reporting Issues

1. Open Extensions tab: click on the button with 3 dots, open _More tools_ submenu, then click on _Extensions_ item.

![Step 1](https://i.imgur.com/74xcLC7.png)

2. Click on _background page_ link (next to _Inspect views_) - this will open console window.

![Step 2](https://i.imgur.com/i3humCn.png)

3. In a regular Chrome tab, navigate to a resource in question (e.g. `edu.trtl/`) - you will notice the console window is populated with lines.

4. Select them and copy to clipboard, or use the context menu's _Save as_ command to produce a log file. Then submit the log along with your [GitHub issue](https://github.com/turtlecoin/.trtl-extension-chrome/issues/new).

![Step 4](https://i.imgur.com/gykI1f0.png)

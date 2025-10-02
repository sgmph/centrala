**Centrala** is a minimalist local web app designed to organise essential links, tools, and resources into categorised sections. I developed this app for my personal use because I enjoy having all my links in one place for quicker navigation. It might also be helpful to others, so feel free to use it.

![Centrala Dashboard](https://raw.githubusercontent.com/sgmph/centrala/refs/heads/main/resources/img/sgmph-links-dashboard.png)

How to download it?

Clone the repository (or download it as a [ZIP](https://github.com/sgmph/centrala/archive/refs/heads/main.zip):
```sh
	git clone https://github.com/sgmph/centrala.git
	cd centrala
```
Open `index.html` in your browser. That's it.

**Please note**:

Data is stored locally in your browser. If you clear your browser's data or cache, your `localStorage` will be erased, and you will lose your saved links. To avoid this, please use the Export/Import options. The app utilises the browser's Storage Manager API `navigator.storage.persist()` to request persistent storage. If this request is granted, the browser will attempt to keep your data safe from automatic cleanup.

The app is built with static HTML and JavaScript, allowing it to function fully offline after the initial load. You can even keep it on a USB drive or in the cloud and open the `index.html` file in any browser. By using the Export function, you can download a file containing your links, which you can then transfer to another browser or computer where this web app is installed.

Currently, there is no cloud synchronisation between devices unless you manually copy or export your JSON backup. Please note that storage space is limited by the browser.

**Recommendation**

If you enjoy keeping all your links organised in one central location, consider setting this web app as your homepage and startup page. To do this in Firefox (or any other browser, noting that there may be slight differences), follow these steps:

1.  Open Mozilla Firefox (or your preferred browser).
2. Access the settings by clicking on the hamburger menu in the top right corner, or type `about:preferences#home` in the address bar.
3. In the "Homepage and new windows" section, select "Custom URLs" and enter the path to the `index.html` file where you stored it.

![Add as Homepage in Mozilla Firefox](https://raw.githubusercontent.com/sgmph/centrala/refs/heads/main/resources/img/add-as-homepage.png)

Now, whenever you open Firefox or a new window, this web app will load as your default page.

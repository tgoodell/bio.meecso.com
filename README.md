# bio.meecso.com

**NOTE: This repository has been archived and will no longer be updated.**

---

This repository houses the website files for [bio.meecso.com](https://bio.meecso.com). NOTE: this website is no longer being updated since its purpose has been fulfilled. 

![html5](https://img.shields.io/badge/code-HTML5-orange.svg)
![css3](https://img.shields.io/badge/code-CSS-blue.svg)
![js](https://img.shields.io/badge/code-JS-yellow.svg)
![avh](https://img.shields.io/badge/web-Apache%20Virtual%20Hosts-critical.svg)
![GNU GPLv3](https://img.shields.io/badge/license-GNU%20GPLv3-%23a42e2b.svg)

## Installation

---

As noted [here](https://blog.tgoodell.com/guide-to-apache-virtual-hosts/), Apache Virtual Hosts are needed. Follow the guide if you have not already installed it on a web server. 

Then, log into your web server: 

`ssh root@xxx.xxx.xxx.xxx`

Make sure that you have already created the target domain and the neccessary configs for Apache Virtual Hosts. Naviagte to the proper directory:

`cd /path/to/bio.meecso.com`

Remove the current files:

`rm -r public_html`

Then, clone this github repo to create a new `public_html`:

`git clone https://github.com/tgoodell/bio.meecso.com public_html`

## License

GNU General Public License v3.0

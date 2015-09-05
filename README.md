This vagrant box can be used with **wkhtmltopdf-nodejs-ws-server** and **wkhtmltopdf-nodejs-pdfapi** npm packages.

# Requirements

You need following software to be installed:

1. **VirtualBox**.
2. **Vagrant**.
3. **Ansible**.

# What's inside?

Vagrant box contains following installed software:

1. Ubuntu 14.04 x64
2. Wkhtmltopdf 0.12.2 with dependencies
3. Xvfb display server
4. Git

# Installation

1. Open and change **Vagrantfile.dist** to fit your needs, then rename it to **Vagrantfile**.
2. Run **vagrant up** from the folder where **Vagrantfile** is located and it will do all job.

# Usage

After vagrant box is installed you can access vagrant box via ssh by running **vagrant ssh** command.
Then you can run any js file like **nodejs script_name.js** from **/app** folder.

#Examples

- Pdf generation using **wkhtmltopdf-nodejs-pdfapi**: https://github.com/GrizliK1988/wkhtmltopdf-nodejs-pdfapi
- Websocket server usage that handles pdf generation located here: https://github.com/GrizliK1988/wkhtmltopdf-nodejs-ws-server
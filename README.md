# Project 9 - Honeypot

Time spent: **6** hours spent in total

> Objective: Setup a honeypot and provide a working demonstration of its features.

### Required: Overview & Setup

- [ ] A basic writeup (250-500 words) on the `README.md` desribing the overall approach, resources/tools used, findings
  - I created a MHN Admin VM through gcloud. Then I deploy a few different honeypot in Ubuntu 14.04 instance. 
  I deployed: Dionaea, Wordpot, p0f. FIrst, I click on Deply in the MHN admin console in my browser to obtain the the Deploy Command. 
  Then I run the Command in the honeypot VM. After that, I simply read the log file to see how many attacks and what kinds of attack 
  the honey pot it captured.
- [ ] A specific, reproducible honeypot setup, ideally automated. There are several possibilities for this:
	- In the gcloud console, run:
		* sudo apt-get install -y git
		* cd /opt
		* sudo git clone https://github.com/RedolentSun/mhn.git
		* cd mhn
		* sudo ./install.sh
	- Go back to Google Cloud Plantform webpage and edit the firewall rule:
		* click default-allow-http
		* change protocols and port to **Allow all**
		

### Required: Demonstration

- [ ] An example of the data captured by the honeypot (example: IDS logs including IP, request paths, alerts triggered)
	*	https://github.com/bonliu/Cybersecurity_week9/blob/master/session.json
- [ ] A screen-cap of the attack being conducted
	![attack](https://user-images.githubusercontent.com/31838335/39412737-28b55fa2-4bef-11e8-9fc8-3bab4b52a54f.gif)

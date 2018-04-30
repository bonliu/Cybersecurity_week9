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
	- Alternatively, **detailed** notes added to the `README.md` regarding the setup, requirements, features, etc.

### Required: Demonstration

- [ ] A basic writeup of the attack (what offensive tools were used, what specifically was detected by the honeypot)
- [ ] An example of the data captured by the honeypot (example: IDS logs including IP, request paths, alerts triggered)
- [ ] A screen-cap of the attack being conducted

### Stretch Features
- Honeypot
	- [ ] HTTPS enabled (self-signed SSL cert)
	- [ ] A web application with both authenticated and unauthenticated footprint
	- [ ] Database back-end
	- [ ] Custom exploits (example: intentionally added SQLI vulnerabilities)
	- [ ] Custom traps (example: modified version of known vulnerability to prevent full exploitation)
	- [ ] Custom IDS alert (example: email sent when footprinting detected)
	- [ ] Custom incident response (example: IDS alert triggers added firewall rule to block an IP)
- Demonstration
	- [ ] Additional attack demos/writeups
	- [ ] Captured malicious payload
	- [ ] Enhanced logging of exploit post-exploit activity (example: attacker-initiated commands captured and logged)

# ShinyCaffeine
This repo contains the code related to the demo version of caffeine simulator for clinicians. 

## Local instance
For development purposes we can run the server and modify the internal code locally (i.e. on our own computers).
For this, run the file `run.R` using R.
You should then be able to see the app in your browser.

## Public instance
We plan to make the server accessible for **demo** purposes on a small virtual machine (VM).
For the server to be publicly available, it has to run on a VM hosted in some public institution.
Suggestions for the VM:
- based on docker container, itself based on a debian image with R and all the required packages pre-installed. This has the advantage to let us release the final docker image, and to let other institutions install the image and configure a VM on their own facilities.

- runs in a network that allows traffic to/from port 443. This is so that the demo can be accessed from anywhere in the world.

- has approx. 4 cores and 8GB of RAM. These are rather small and affordable requirements that should be sufficient for a demo version.

## Todo
- [ ] Ask permission to use the caffeine simulation Matlab code
- [ ] Decide on final list of functionalities
- [ ] UI (User Interface) design, i.e. general layout of buttons, plots, fields
- [ ] Code the call-backs, i.e. the fuctionalities triggered by interacting with the app.
- 
 
## Contacts
Britta & Antoine
 

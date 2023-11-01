# ShinyCaffeine

## Local instance
For development purposes we can run the server and modify the internal code locally (i.e. on our own computers).
For this, create a file containing these lines:
```bash
library(shiny)
runApp("<Repo folder>")
```
and run it using R.

## Public instance
We plan to make the server accessible for **demo** purposes on a small virtual machine (VM) hosted
To make the server publicly available, we have to run it from a virtual machine (VM) hosted in some institution.
Suggestion for the VM that:
- is based on docker container, itself based on a debian image with R and all the required packages pre-installed. This has the advantage to let us release the final docker image, and to let other institutions install the image and configure a VM on their own facilities.

- runs in a network that allows traffic to/from port 443. This is so that the demo can be accessed from anywhere in the world.

- has approx. 4 cores and 8GB of RAM. These are rather small and affordable requirements that should be sufficient for a demo version.

## Todo
- [] Ask permission to use the caffeine simulator
- [] Decide on final list of functionalities
- [] UI (User Interface) design, i.e. general layout of buttons, plots, fields
- [] Code call-backs, i.e. code the function that
- 
## Contacts
Britta & Antoine

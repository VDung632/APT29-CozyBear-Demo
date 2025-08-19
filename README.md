# APT29-CozyBear-Demo
This is a demo for an university project to show how an adversary can use external service to evade detection. The API in the demo has already expired.

The steps are truncated from the origin for simplicity:
- Compile the payload with the DropBox API key.
- Create a distraction file (here is a picture of a car and a lnk file of it)
- Create a SFX zip file that would execute the payload after extraction. 
- Put everything in an ISO file.
- Start the C2 server on adversary side using the python script.
- Host a website (a simple HTML file) that automatically download the ISO file.
- Double click the zip file and enjoy.

To get your own DropBox API key, create an account on DropBox then go here: https://www.dropbox.com/developers and create an app

This demo is a recreation from this github repo: https://github.com/S3N4T0R-0X0/APT29-Adversary-Simulation by S3N4T0R

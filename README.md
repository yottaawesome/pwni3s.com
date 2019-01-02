# pwni3s.com

## What is it?
The https://www.pwni3s.com source code, intended for me to learn the Python Flask framework. There will be an Inferno-powered SPA and a Flask backend. 

## You're open sourcing a public web site?
Yep. Obviously, I'm not going to put sensitive information in the source, but the repo is intended for education and showcasing learning a new framework. The site is intentionally whimsical.

## Structure
You will find the Inferno source in the `client` folder, and the server source in the `server` folder.

## It's pretty empty...
It's a work in progress. I chase multiple projects at once, not all of which are on GitHub. :-)

## Running it
You'll need Python3, Pip3 and virtualenv in a Linux-based environment. If you're trying to run this on Windows, I admire your bravery, but you're on your own. 

1. Clone repo
2. CD into <repo root>/server
3. Create virtualenv (note that the script below assumes you've called it "env"): `virtualenv env`
4. Activate the virtualenv: `source ./env/bin/activate`
5. Install dependencies: `pip3 install --user -r requirements.txt`
6. Run dev server: `sh run-env`

At some point, I'll also add a Dockerfile and containerize the application.

## What's up with the name?
Everyone loves ponies, but pwni3s are even cooler.
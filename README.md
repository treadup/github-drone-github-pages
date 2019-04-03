# github-drone-github-pages
This project is an example of how to deploy a web site to GitHub pages
using the drone.io service.

## Deployment key
For drone to be able to authenticate against GitHub you have to create
a deployment key. This is done using the ssh-keygen command. Add the
private key as a secret in Drone. Add the public key as a deployment
key for the target repo in GitHub. Make sure that you give the
deployment key push access when creating it in the GitHub user interface.

## Location
The deployed site can be accessed using the
[https://treadup.github.io/github-pages/](https://treadup.github.io/github-pages/)
url.

# cfl-ctf-challenge-2025

To complete the challenge you will need to do the following:

<ol>
  <li>Deploy Rancher</li>
  <li>Deploy a downstream K3s cluster with Rancher</li>
  <li>In Rancher use the Fleet/Continuous Delivery dashboard and create a new `Git Repo` pointing to this repository</li>
</ol>

If you followed these instructions correctly, Fleet will deploy an app called `ctf` in the `cattle-fleet-system` namespace of your K3s cluster. Check the output of the pod logs to see what the flag is!

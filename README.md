# cfl-ctf-challenge-2025

To complete the challenge you will need to do the following:

<ol>
  <li>Deploy Rancher</li>
  <li>Deploy a downstream K3s cluster with Rancher</li>
  <li>In Rancher use the Fleet/Continuous Delivery dashboard and create a new `Git Repo` with the following details:</li>
    <ol>
      <li>point to this Repository URL: `https://github.com/kourosh7/cfl-ctf-challenge-2025.git` and use the latest `Branch Name` found here: https://github.com/kourosh7/cfl-ctf-challenge-2025</li>
      <li>target your K3s cluster you created in step 2</li>
      <li>leave default values for everything else</li>
    </ol>
</ol>

If you followed these instructions correctly, Fleet will deploy an app called `ctf` in the `cattle-fleet-system` namespace of your K3s cluster. Check the output of the pod logs to see what the flag is!

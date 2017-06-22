Now, that was a quick and interactive way of installing the OpenShift Container Platform 3.5 !
Below is a quick summary of the three steps you performed to install and verify OpenShift -
 - Start the quick installer ->
   # atomic-openshift-installer install
 - View the installation configuration file that was created in the first step ->
   # cat ~/.config/openshift/installer.cfg.yml
 - Verify your installation ->
   # oc get nodes





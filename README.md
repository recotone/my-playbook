# my-playbook
* my-playbook <br> 
* source hacking/env-setup <br> 
* Manual Create kubernetes PV,PVC and GlusterFS by ansible playbook <br>
* don't remove the dest-gfs <br>
example: <br> 
* ansible-playbook k8s-cr-gfs.yaml --extra-vars "app_name=jenkins volumes=['data']" <br>
* ansible-playbook k8s-del-gfs.yaml --extra-vars "app_name=jenkins volumes=['aaa'] isDeldir=true" <br>

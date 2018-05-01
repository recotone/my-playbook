# my-playbook
* my-playbook <br> 
* source hacking/env-setup <br> 
* Manual Create kubernetes PV,PVC and GlusterFS by ansible playbook <br>
* don't remove the dest-gfs <br>
example: <br> 
* <code> ansible-playbook -v k8s-create-pvc.yaml --extra-vars "namespace=gitlab app_name=gitlab volumes=['vol']" </code><br>
* <code> ansible-playbook k8s-cr-gfs.yaml --extra-vars "app_name=jenkins volumes=['data']" </code><br>
* <code> ansible-playbook k8s-del-gfs.yaml --extra-vars "app_name=jenkins volumes=['aaa'] isDeldir=true" </code><br>


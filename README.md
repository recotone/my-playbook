# my-playbook
my-playbook
Manual Create kubernetes PV,PVC and GlusterFS by ansible playbook \<br>
example: \<br> 
ansible-playbook k8s-cr-gfs.yaml --extra-vars "app_name=jenkins volumes=['data']" \<br>
ansible-playbook k8s-del-gfs.yaml --extra-vars "app_name=jenkins volumes=['aaa'] isDeldir=true" \<br>

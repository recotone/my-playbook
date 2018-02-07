# my-playbook
my-playbook 
Manual Create kubernetes PV,PVC and GlusterFS by ansible playbook \n
example: ansible-playbook hello.yaml --extra-vars "app_name=jenkins volumes=['data']" \n
ansible-playbook k8s-del-gfs.yaml --extra-vars "app_name=jenkins volumes=['aaa'] isDeldir=true" \n

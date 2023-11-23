# TO-DO

- [ ] use vpc module to create vpc
- [ ] OS for nodes
    - [ ] Ubuntu:  (default 20.04) (get this from variables)
    - [ ] Centos/RHEL: (get this from variables)
- [ ] master and worker node instance types and counts as variables
- [ ] userdata: update + upgrade packages
- [ ] userdata: install ssm manager 
    - so we can use `aws ssm start-session --target i-064f012c97944eeb9` command to connect to nodes
- [ ] output: master and worker node IPs to be used in ansible inventory
- [ ] update README.md with instructions for using our scripts to create RKE2 infrastructure on AWS 
- [ ] 
- [ ] 

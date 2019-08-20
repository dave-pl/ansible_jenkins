# ansible_jenkins
setup jenkins server and node with ansible
There are 3 roles, choose what You need:
  - jenkins_with_nginx - setup jenkins over https with nginx as reverse proxy,with self signed certificate
  - jenkins - setup jenkins over https but without any frontend,with self-signed certificate
  - jenkins_node - setup soft for jenkins node: java,git,docker

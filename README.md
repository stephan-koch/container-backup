# container-backup


In this demonstration i tried to figure out how to use Kasten (a Veeam Company) to backup
   1) an Application (in my Case Wordpress with MariaDB) and
   2) how to recover it in an fresh installed K8S Cluster

For this I deployed 
  - some VMs with SuSE Enterprise Micro 5.0
  - installed k3s on it
  - installed vSphere CP+CSI
  - installed Kasten
  - installed Demo Application Wordpress
  - configured Backup and did an backup
  - deleted namespace for wordpress
  - restored the Application
  - deleted the entire VMs
  - reinstalled the VMs, K3S and CSI
  - reinstalled Kasten
  - restored the Application wordpress

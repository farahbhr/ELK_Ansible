# ELK_Ansible

**To run the playbook:</br>

sudo ansible-playbook -i inventory main.yml -b

**To verify if elasticsearch is installed on the remote machine: </br>

curl -X GET "192.168.100.20:9200"

**Access to kibana via the browser with the URL on the remote machine:</br>

http://192.168.100.20:5601

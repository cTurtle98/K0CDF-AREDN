# K0CDF-AREDN

K0CDF Amateur Radio Emergency Data Network Infrastructure


this is the code that defines my infrastructure I host on the Amateur Radio Emergency Data Network


## setup

run this to setup your local machine for administrering the infrastructure
```bash
sudo apt install -y python3-pip
pip3 install ansible
ansible-galaxy collection install community.postgresql
pip3 install psycopg2
```
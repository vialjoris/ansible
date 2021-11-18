# requirements

* ansible must be installed and running. <https://www.ansible.com/>

# usage

`
ansible-playbook ****.yml
`

## ubuntu update openssl 1.0.2 to 1.1.0

* I share my ansible playbook for update my servers with openssl 1.0.2.

* Check the openssl version, if it is 1.0.2 : run update openssl 1.1.0.

  * mkdir /data/scripts/openssl
  * dowaload openssl 1.1.0
  * install openssl 1.1.0

### version check

* Pour valider la version de openssl :

`
openssl version
`



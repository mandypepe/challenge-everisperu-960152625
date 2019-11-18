ELK 
=========

Instala y corre un ELK en docker

Requirements
------------

Docker 
Ansible 2.8 / +

Dependencies
------------

docker.elastic.co/elasticsearch/elasticsearch:7.4.2
docker.elastic.co/kibana/kibana:7.4.2
docker.elastic.co/logstash/logstash:7.4.2 

Example Playbook
----------------

    - name: servers
      roles:
        - user

License
-------

MIT
This  First version of the ELK setup was created in the elk-V1 branch on 15th November 2024.
While running the docker-compose file need to run the below command to start the kibana UI access.
               1.  curl -u elastic:cstoreiq -X POST "http://54.234.252.157:9200/_security/user/kibana_system/_password" -H 'Content-Type: application/json' -d '{
                  "password" : "cstoreiq"
                  }'

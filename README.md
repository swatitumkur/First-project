└── project
├── docker-compose.yml
├── mysql
│ ├── data
│ └── init.sql
├── nginx
│ ├── default.conf
│ └── index.html
└── php
├── Dockerfile
└── process_form.php

1.Create main directory as project
2.Inside project create 3 sub directory as nginx, php, mysql
3.Put all the files as per directory name
4.create directory inside mysql named as data and leave it blank (afterward we are going to bind that directory as a volume)
5.Open docker-compose file and check the all paths are correctly written in the file (check the spacing)
6.then build the file and hit IP to browser

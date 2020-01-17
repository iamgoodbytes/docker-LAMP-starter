# docker-LAMP-starter
A starter template if you want to get up and running quickly with php/mysql/apache in Docker

# starting
Run `docker-compose up` to bring your LAMP stack online

# connecting to MySQL
You can connect to MySQL from an external tool by using ip and port `0.0.0.0:3306` with user "root" and password "root".
If you want to connect from within your php script use `db` as your hostname instead of the usual `localhost`.

# where to place files
You can place your files and folders anywhere in the public folder.

# how to access your projects
Access projects by browsing to http://localhost:8080 and it will use your public folder as the default location
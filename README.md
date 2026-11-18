<div align="center">
    <h1 style= "margin 0px; padding: 0px;">Personal postgres database</i></h1>
    <hr style="width: 100%; height: 1px; margin: 15px;">
    <a href="https://github.com/Jaimead7/MyPostgres/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?label=LICENSE&message=MIT&color=2dba4e&colorA=2b3137"></a>
</div> 

Postgres database and PgAdmin4 containers setup files.  

## Authors
> Jaime Alvarez Diaz  
> [![email](https://img.shields.io/static/v1.svg?label=Gmail&message=alvarez.diaz.jaime1@gmail.com&logo=gmail&color=2dba4e&logoColor=white&colorA=c71610)](mailto:alvarez.diaz.jaime1@gmail.com)  
[![GitHub Profile](https://img.shields.io/static/v1.svg?label=GitHub&message=Jaimead7&logo=github&color=2dba4e&colorA=2b3137)](https://github.com/Jaimead7)  


## Install  
### Create `.env` files  
`.env.pgadmin`
> ```env
> PGADMIN_DEFAULT_EMAIL="<admin email>"
> PGADMIN_DEFAULT_PASSWORD_FILE="/run/secrets/pgadmin_password"
> ```
`.env.postgres`
> ```env
> POSTGRES_USER="<admin user>"
> POSTGRES_DB="<default database>"
> POSTGRES_PASSWORD_FILE="/run/secrets/pg_password"
> ```
### Create secrets files  
`secrets/pg_password.txt`
> ```txt
> my-postgres-admin-super-save-password
> ```
`secrets/pgadmin_password.txt`
> ```txt
> my-pgadmin-admin-super-save-password
> ```

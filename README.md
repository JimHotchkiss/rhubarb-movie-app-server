# Rhubarb Movie App - Server
 * rails new app_name --api --database=postgresql

[X] Create User - rails g resource User username:string
    (x) username
    (x) password_digest
        (x) gem 'bcrypt'
        (x) Add password_digest column in db
        (x) has_secure_password in User Model
    (x) rails db:create
    (x) rails db:migrate


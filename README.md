# Rhubarb Movie App - Server
 * rails new app_name --api --database=postgresql

[] Create User - rails g resource User username:string
    () username
    () password_digest
        () gem 'bcrypt'
        () Add password_digest column in db
        () has_secure_password in User Model
    () rails db:create
    () rails db:migrate


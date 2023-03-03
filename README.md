# bot_with_pay repo

1. copy repo on your machine
2. rename example.env and add your data
3. create a postgres database with name "gino"
4. in gino create a user with name like of DB_USER in .env file
5. Use app.py file as main to start bot
6. in telegram you are take a message "Bot starting"(ru)
7. use command "/add_item":
    write a name of your item <Enter>
    send a foto(only foto) of your item
    take a prize like 1000. It's number equal 10.00(10dollar 0 cent)
    confirm registr item in db
8. For add your languages goto "local" folder. 
Instruction on russian in "Languages instruction" file.
9. In file config if you want edit a name I18N_DOMAIN= "testbot" to
your bot name, rename a "telebot" in lang files
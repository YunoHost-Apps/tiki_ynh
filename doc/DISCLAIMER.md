### Postinstall

You can log in using the special `admin` username and the `admin` password. You will be asked to change the password immediately after login.

### Storing your uploaded files

To ease the install process and first access, Tiki saves your uploaded files (office documents, images, pdf, etc. attached to wiki pages, forum posts, tracker items, file galleries, ...) by default in its database. This works perfectly in most cases but it is not the recommended setup if you need to save many thousands of files or more.

In that case, consider switching from "Store to database" to "Store to directory", which you will find in the Configuration Wizard. Please use this preset path directory: `/home/yunohost.app/tiki`. You will be able to migrate your currently uploaded files from one to the other.


If you are facing any problem or want to improve this app, please open a new issue here: https://github.com/YunoHost-Apps/tiki_ynh/issues"

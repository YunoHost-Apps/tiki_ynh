### Storing your uploaded files

To ease the install process and first access, Tiki saves your uploaded files (office documents, images, pdf, etc. attached to wiki pages, forum posts, tracker items, file galleries...) by default in its database. This works perfectly in most cases but it is not the recommended setup if you need to save many thousands of files or more.

In that case, consider switching from "Store to database" to "Store to directory", which you will find in the Configuration Wizard. Please use this preset path directory: `__DATA_DIR__`. You will be able to migrate your currently uploaded files from one to the other.

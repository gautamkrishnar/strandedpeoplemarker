# strandedpeoplemarker
This is a web application that allows people affcted by flood to mark their position and share their co-ordinate details with the rescue team. 

### Technologies used
- PHP
- JS
- GoogleMaps API
- MySQL (Database Structure added in db folder just import it)

### How to use?
* Just visit http://lifehunterz.com/ and use the application.

### How to get started?
* Install MySQL,PHP and Apache.
* Clone the project to the webroot.
* Migrate the database using the following command:
```bash
cd strandedpeoplemarker
mysql -u username -p // Replace username with your db username and type your password
create database rescue;
use rescue;
source ./db//rescue.sql
```

### Project ToDos
- [ ] Admin panel
- [ ] Spam prevention

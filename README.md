# CodeIgniter News Boilerplate

This repo includes the files necessary to implement the tutorial from the [codeigniter help website](http://www.codeigniter.com/user_guide/tutorial/) along with a few slight modifications.

### Install ###

* First, you need to [download](https://github.com/bcit-ci/CodeIgniter/archive/3.0.0.zip) and install codeigniter [following these steps](http://www.codeigniter.com/user_guide/installation/index.html).

* Once you have it up and running, download this repo, and place the contents of the `application` directory in your codeigniter application directory, making sure *not to overwrite any existing folder structures* (open any existing folders and paste the contents of this repo into them).

* The SQL directory should not be copied in. This simply contains an SQL command that you can run inside of mySQL in order to create the table that will house your news items.

* Following the tutorial on the codeigniter website, make sure to change the `base_url in the `config.php` file, and the database connection strings in the `database.php` file (`hostname, username,password,database`)

### Additional Modifications ###

* The only modifications I've made to the codeigniter tutorial are to add an `htaccess` file which allows url rewriting, preventing the need to preface your urls with index.php (i.e. `http://mydomain.com/index.php/news/`). In order to take advantage of this, you will have to rename this file as `.htaccess` (adding the '.'), and to make sure your server supports such rewriting.

* I've also added any additional recommended URL rewriting to the `routes.php` file that were suggested in the tutorial.

### Notes ###

* Codeigniter is at version 3.0 at the time of publishing this repo.

* I do not have the ability to provide support for this tutorial. Any support requests should be directed at the codeigniter team and forum. This repo is posted merely for the convenience of getting up and running with codeigniter.

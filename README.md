# Yii Inquid Extension generator

To use this example:

* Clone the project: `git clone https://github.com/inquid/extension-generator-example`
* Get into the folder `cd extension-generator-example`
* Install the dependencies `composer install`
* Serve the project `php -S localhost -t web`
* Open gii [http://localhost/index.php?r=gii](http://localhost/index.php?r=gii)
* Open the extension generator.
* Fill the fields.
* You will see that the files in the folder `templates/inquid/extension/default` are bing modified and copied to th destination folder `runtime/tmp-extensions/yii-example/`
* While the folders in `templates/inquid/extension/default/static_files` are just being copied.

* Please take a look on the file `app\templates\inquid\extension\Generator` this file modifies the files and copies the static files.

The final generated extension should have the same files as: [https://github.com/inquid/php-library-template](https://github.com/inquid/php-library-template)

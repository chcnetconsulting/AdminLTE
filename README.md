# AdminLTE plugin for CakePHP

AdminLTE 2 Theme for CakePHP 4.x
## Installation

This is a Theme Plugin for CakePHP 4.x and higher. It contains the complete and unaltered AdminLTE Package
from https://adminlte.io. Please refer to https://adminlte.io/themes/AdminLTE/documentation/index.html for 
Documentation, how to use this theme. The Package contains Bootstrap 3, jQiery 1.11+ and all other plugins 
mentioned there. So it is not necessary to include neither bootstrap nor jquery for proper function of this 
composer package.


You can install this plugin into your CakePHP application using [composer](https://getcomposer.org).

The recommended way to install composer packages is:

```
composer require chcnet/admin-lte
```
To start using this theme, set it up by adding into your src/Controller/AppController.php:

```
class AppController extends Controller
{
...
    public function beforeRender(\Cake\Event\EventInterface $event)
    {
       $this->viewBuilder()->setTheme('AdminLTE');
    }
...
}
```
Then prepre a proper default.php in AdminLTE Stype in templates/layout/. You can use the default Demo Layout as starting point for your website layout: https://adminlte.io/themes/AdminLTE/index2.html.

Do not forget to search and replace all occurrences of "../../" with  "/AdminLTE/" (mention the closing bracket).

That should get you up and running :-)

Happy coding. 

# AdminLTE

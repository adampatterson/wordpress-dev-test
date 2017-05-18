## The Mission: 
=======
Make a WordPress plugin that will read that data and display it in a WordPress page using a shortcode.


* Create a github account.
* Read data from the Github public API. https://developer.github.com/v3/ 
* Install Guzzle into the WordPress using composer.
* Request the .json file from GitHub using Guzzle
* There should be a shortcode that will allow the editor to choose the number of repositories to list as well as what username to use.  The plugin should be default to ‘octocat’.
* This plugin should also be callable using a function in the template code.
* Bootstrap should be included in the project using bower and processed through Gulp or Grunt.
* The output HTML should be styled using basic Bootstrap.
* Bootstrap should be loaded in the page through the plugin.
* There is the potential to add on a couple of extra steps here.
* Commit the plugin to the repo with a proper .gitignore file ( assuming this is locally developed and not a distributed plugin )


**Resources:**

* https://developer.github.com/v3/
* https://www.topdraw.com/blog/using-composer-laravel-and-guzzle-in-your-wordpress-plugin/
* https://api.github.com/users/octocat/repos

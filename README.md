Simple Drupal 8 module that modifies mail headers and subject

### Usage - Note module has no User Interface
Its just an implementation of hook_mail_alter and its does not contain a configuration page (UI) so you have to modify the .module file with your own details 'from' 'reply' 'subject' etc and comment out what you don't need to change.

I have added dpm functions so if you enable devel module (https://www.drupal.org/project/devel) and uncomment those lines you might find other header variables that you need to change

By default its overriding the the emails send from the core contact module but you can modify the switch to modify email send from other modules. 

### Installation
Download zip archive and unzip within your modules directory, note the directory created might contain "master" please rename and remove "master" from it.  After modifying the .module file as instructed above please login to your drupal site and enable the module.  Please test with an email that it actually does what you want it to do.

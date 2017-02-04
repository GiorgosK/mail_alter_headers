Simple Drupal 8 module that modifies mail headers and subject

### Usage - Note module has no User Interface
Its just an implementation of hook_mail_alter and its does not contain a configuration page (UI) so you have to modify the .module file with your own details 'from' 'reply' 'subject' etc and comment out what you don't need to change.

I have added dpm functions so if you enable devel module (https://www.drupal.org/project/devel) and uncomment those lines you might find other header variables that you need to change


This customfield plugin alows to have a text input with regex validation. Enabling to ensure valid format of the field data. 

For validating the user input, a perl compatible regular expression is used. Regex can be definied during creation of the field itself, e.g. a course cudtom field. We recommend to not open these field definition option to all users, as defineing a regex is not easy. The plugin performs a regex validation on server side, when saving the field.
Please add a detailed description for the field that explains the rules in a human readable form, as most of the useres will not understand the regex, and therefore will be unable to correct theire input, unless you have a good description. For multi language sites, currently the only way to provide a translated description is to use multilang filter on the site, and providing description in all languages in the description field. 

Once the field is defined, users can use this field like a regular text field. Enter data and store it. If entered value does not match against the regex, input will be not accepted and user receives a standard notification, including the regex. Field data validation is performed on both server and client side.

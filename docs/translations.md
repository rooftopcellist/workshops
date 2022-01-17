# Localization for Ansible Workshops

## Extract Strings

use the following make target from the root of your clone to extract strings:

```
make generate-po
```

## Translate a new Module

To configure a new module to be translated, a po4a.cfg config file needs to be placed in each of the exercises in the module.  

For example: [exercises/ansible_rhel/1.1-setup/po4a.cfg](./exercises/ansible_rhel/1.1-setup/po4a.cfg)



## Add New Locale

In each po4a.cfg file, there is a line that configures language.  To add a new language, it needs to be added to each of these configs.  

```
[po4a_langs] ja zh
```

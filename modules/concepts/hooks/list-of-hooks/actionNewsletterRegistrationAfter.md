---
menuTitle: actionNewsletterRegistrationAfter
Title: actionNewsletterRegistrationAfter
hidden: true
hookTitle: 
files:
  - modules/ps_emailsubscription/ps_emailsubscription.php
locations:
  - front office
type: action
hookAliases:
---

# Hook actionNewsletterRegistrationAfter

## Information

Hook locations: 
  - front office

Hook type: action

Located in: 
  - [modules/ps_emailsubscription/ps_emailsubscription.php](https://github.com/PrestaShop/PrestaShop/blob/8.0.x/modules/ps_emailsubscription/ps_emailsubscription.php)

## Call of the Hook in the origin file

```php
Hook::exec(
            'actionNewsletterRegistrationAfter',
            [
                'hookName' => $hookName,
                'email' => $_POST['email'],
                'action' => $_POST['action'],
                'error' => &$this->error,
            ]
        )
```
---
menuTitle: actionAdminDeleteBefore
Title: actionAdminDeleteBefore
hidden: true
hookTitle: 
files:
  - src/PrestaShopBundle/Controller/Admin/ProductController.php
locations:
  - back office
type: action
hookAliases:
---

# Hook actionAdminDeleteBefore

## Information

Hook locations: 
  - back office

Hook type: action

Located in: 
  - [https://github.com/PrestaShop/PrestaShop/blob/8.0.x/src/PrestaShopBundle/Controller/Admin/ProductController.php](src/PrestaShopBundle/Controller/Admin/ProductController.php)

## Call of the Hook in the origin file

```php
dispatchWithParameters(
                        'actionAdminDeleteBefore',
                        $hookEventParameters
                    )
```
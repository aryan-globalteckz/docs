---
menuTitle: actionAdminShopParametersOrderPreferencesControllerPostProcessBefore
Title: actionAdminShopParametersOrderPreferencesControllerPostProcessBefore
hidden: true
hookTitle: On post-process in Admin Configure Shop Parameters Order Preferences Controller
files:
  - src/PrestaShopBundle/Controller/Admin/Configure/ShopParameters/OrderPreferencesController.php
locations:
  - back office
type: action
hookAliases:
---

# Hook actionAdminShopParametersOrderPreferencesControllerPostProcessBefore

## Information

{{% notice tip %}}
**On post-process in Admin Configure Shop Parameters Order Preferences Controller:** 

This hook is called on Admin Configure Shop Parameters Order Preferences post-process before processing any form
{{% /notice %}}

Hook locations: 
  - back office

Hook type: action

Located in: 
  - [https://github.com/PrestaShop/PrestaShop/blob/8.0.x/src/PrestaShopBundle/Controller/Admin/Configure/ShopParameters/OrderPreferencesController.php](src/PrestaShopBundle/Controller/Admin/Configure/ShopParameters/OrderPreferencesController.php)

## Call of the Hook in the origin file

```php
dispatchHook('actionAdminShopParametersOrderPreferencesControllerPostProcessBefore', ['controller' => $this])
```
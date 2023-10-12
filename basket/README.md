# Bitrix js form component

__Component calling example for default template:__
```php
<?$APPLICATION->IncludeComponent(
	"sale:order",
	"",
	array(
		"DELIVERIES" => array(
		),
		"PAYSYSTEMS" => array(
		),
		"PERSONS" => array(
		),
		"COMPONENT_TEMPLATE" => ".default",
		"ORDER" => "DELIVERY"
	),
	false
);
);?>


```

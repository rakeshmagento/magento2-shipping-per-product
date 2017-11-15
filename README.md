# magento2 shipping per product
Magento2 shipping per product, this module allow admin to put shipping per product and apply accordingly on cart/checkout.

# installation

1.Copy files to app/code/ direcotry.

2.Run the following commands

php bin/magento setup:upgrade

php bin/magento setup:static-content:deploy

php bin/magento cache:flush

php bin/magento cache:clean

3.The plugin will create a new product attribute "Shipping Cost", where admin can enter shipping for individually items.

4.Admin needs to enable it by navigating to System->Configuration->Shipping Methods->Shipping Per Product.

5.Options for Multiply Quantity, if enabled yes, this funtion will multiply the shipping rate with the item shipping price.





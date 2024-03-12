# M2_RemoveLeadingZeros

This is a simple module to get rid of the leading zeros in Magento2 that automatically get added in to order numbers.

In other words, this module will make the default Magento2 order numbers modified from this: #000000001 to this: #1.

# How to install
  1. Create a folder and subfolder inside your app/code folder like so: SethIam/RemoveLeadingZeros. The final directory path should look like this: app/code/SethIam/RemoveLeadingZeros
  2. Paste the code in the repository inside of the "RemoveLeadingZeros" folder. registration.php will be its own file inside the folder, and etc will be another subfolder.
  3. Your final module directory should look like this: app/code/SethIam/RemoveLeadingZeros/registration.php & app/code/SethIam/RemoveLeadingZeros/etc/di.xml --module.xml
  4. Once complete, run "php bin/magento setup:upgrade" in your CLI
  5. TADA! Test by creating a new order, and check to see if it removed the zeros.

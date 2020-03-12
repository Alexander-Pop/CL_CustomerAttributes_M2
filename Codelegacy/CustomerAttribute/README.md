* run commands:
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:flush
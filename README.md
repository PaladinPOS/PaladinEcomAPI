# PaladinEcomAPI
Paladin eCommerce API

The Paladin eCommerce API is a RESTful API that allows connectivity to stores running Paladin Point of Sale for the purposes of syncing to ecommerce websites. Two calls are currently built.

Get Inventory Item Data:
This call allows the retrieval of part number, qty stock on hand, desc1 and retail price1. Calls can be made for a single part number, or all part numbers (in which case the result will be a paginated list).

Process Completed Invoice:
This call allows the creation of an invoice in the Point of Sale system, e.g. after an online sale, so that Paladin can maintain correct stock on hand and accounting.

See spec document for additional details. 

For questions or help, contact Paladin Support (support@paladinpos.com).

# 📤 Goods Outbound

You got a load of orders and you want to get those zines on their way to customers. Sounds good!

### Shipping Frequency

We tend to ship weekly on a Saturday, batching up orders. If we (or you!) receive lots of orders earlier in the week we’ll look at shipping before then.

### File format

We try not to be too prescriptive about this, but we do have requirements that need to be adhered to otherwise we cannot ship your stock efficiently 😕 We do charge for reworking files that don’t meet our specification, but you’ll always be able to fix it yourself instead.

We accept CSVs using commas as column delimiters, and semi-colons as row delimiters.

Each file must contain (at least):

* Order ID
* Name (first name/last name)
* Address Line 1
* City
* Postcode
* Country
* SKU
* Quantity
* Line item price
* Order total price
* Shipping option (see below)

You can optionally include:

* Address Line 2
* Address Line 3
* County/State
* Product Name
* Email
* Phone

Other fields we’ll generally ignore.

If you’re sending multiple SKUs in a single shipment, you should repeat the following columns (with the appropriate values) on another row:

* Order ID (used to link the rows)
* SKU
* Quantity
* Line item price

### Shipping Option

If you are choosing to send via an option other than untracked you should include the following shipping option codes:

| Destination   | Untracked | Tracked | Untracked DDP | Tracked DDP |
| ------------- | --------- | ------- | ------------- | ----------- |
| UK            | CRL       | PF24    | N/A           | N/A         |
| EU            | DG4       | MTK     | DE6           | MPR         |
| Rest of World | DG4       | MTK     | DE6           | MPR         |

We ship and invoice using these codes so it is important they are correct in your data.  

### Order Total Price 

You are responsible for ensuring this is accurate as it will be declared to customs authority on legal documents. 

If we do not believe it is a true representation of the value of the goods we may be unable to ship your orders. 

We use this field to calculate additional DDP fees due where applicable. 

### Sending us files

We’ll share a Google Drive folder with you, so you can upload your files, dated the day they have been generated.

You just need to email us to let us know the file is there, and we’ll confirm the orders have shipped.

### Return files

We can provide return files on request, if you’d like. These include tracking details (if the shipping product has them) and the additional information about the shipment (weight, size etc)

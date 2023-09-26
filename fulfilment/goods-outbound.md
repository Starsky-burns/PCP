# 📤 Goods Outbound

You got a load of orders and you want to get those zines on their way to customers. Sounds good!

### Shipping Frequency

We tend to ship weekly on a Saturday, batching up orders. If we (or you!) receive lots of orders earlier in the week we’ll look at shipping before then.

### File format

We try not to be too prescriptive about this, but we do have requirements that need to be adhered to otherwise we cannot ship your stock efficiently 😕 We do charge for reworking files that don’t meet our specification, but you’ll always be able to fix it yourself instead.

We accept CSVs using commas as column delimiters, and semi-colons as row delimiters.

Each row must contain (at least):

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
* Order total price

[Here's an example for you to check out!](https://docs.google.com/spreadsheets/d/1q6\_YUomR1TpgoccIUSOqoUHwcMHVf0Dkts31CrbbyFA/edit#gid=0)

### Reformatting BackerKit / Kickstarter Data

We're able to do this for you using some internal tooling we've developed. It's charged at our standard data reformatting rate.&#x20;

### Order Total Price

You are responsible for ensuring this is accurate as it will be declared to customs authority on legal documents.

If we do not believe it is a true representation of the value of the goods we may be unable to ship your orders.

We use this field to calculate additional DDP fees due where applicable.

### Sending us files

Please share these with us via Google Drive (or equivilant). Email attachments aren't secure so _please_ avoid those!&#x20;

### Return files

We can provide return files on request. These include tracking details (if the shipping product has them) and the additional information about the shipment (weight, size etc)

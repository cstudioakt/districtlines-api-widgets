## Generator and Previewer

Go to the link below to view the Generator and previewer:

[https://districtlines.github.io/districtlines-api-widgets/iframe-example.html
](https://districtlines.github.io/districtlines-api-widgets/iframe-example.html)

## Basic Usage

Paste the code below anywhere between the `<body>` and `</body>` tags on your website.

> Remember to replace `{IDNUMBER}` with your store genre ID. If you do not know this number please contact your District Lines Store Representative. 

	<iframe width="798" height="500" src="https://www.districtlines.com/app/shop.php?storeID={IDNUMBER}"></iframe>
	
## Remove the header

If you do not want your store's header to show and just have a product listing, add the variable `&header=0` to your `src=""` path.

> Remember to replace `{IDNUMBER}` with your store genre ID. If you do not know this number please contact your District Lines Store Admin. 

	<iframe width="798" height="500" src="https://www.districtlines.com/app/shop.php?storeID={IDNUMBER}&header=0"></iframe>

		
## Have an API Store?
If you have a District Lines API Store and want your "Buy Now" buttons to link to the API Store. Let your District Lines Store Admin know and they will make sure the API Key has the domain name attached properly.

## Functional Test

This example is a real districtlines.com store and functions 100% with the header showing.

	<iframe width="798" height="500" src="https://www.districtlines.com/app/shop.php?storeID=2166&header=1"></iframe>

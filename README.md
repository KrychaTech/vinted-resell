# vinted-resell
A small website for calculating profit, fees, and ROI's on reselled items.

## How to use?
It's simple! This website has two panels - one being the resell calculator, which allows the user to calculate a price that satisfies both the customer and the reseller. This is done via reducing the price by -10% from the max price which an item is recommended to sale for, and then rounding it to the nearest 10 (this can be configured on the panel directly!) to ensure a satisfactory price. The other panel allows to calculate profit and ROI on each sale: by default it fetches the resell price from the first panel & asks the user for the price the item was purchased for. Then it calculates vinted fees and asks for logistics + additional costs, such as shipping, packing materials, etc. After every cost is added, it gives the total profit, ROI (%) as well as vinted fees for the original purchase.



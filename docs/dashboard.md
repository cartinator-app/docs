---
layout: home
title: App dashboard
nav_order: 2
description: 
---

# App dashboard
{: .no_toc }

App dashboard is the most critical page of the app. It consolidates all the insights and reports in a digestible format. A couple of simple clicks is all that it takes to use the dashboard.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Reporting period

All of the reports on the dashboard page require you to set the reporting period.

![Reporting period selector](/assets/images/date-selector.png)

1. Click the calendar button located in the upper left part of the dashboard
2. Select the desired range
3. Confirm by clicking the '**Apply**' button

Selecting the reporting period will automatically set a period of the same duration in the past. All data in the specified period will be automatically compared to the previous period.

For example, if you select **Today**, all reports will show you data for **Today** compared to **Yesterday**.

## Widgets

All the reports on the dashboard are organized into widgets. Most of them work the same way by displaying value (data) for the selected reporting period, value for the previous one, and indicator of a change. 

### Average cart value

Average cart value displays the average **value of the products added to the carts** during the selected reporting period. The widget displays the value in the shop's currency - even if you run a multi-currency store.

### Carts

Carts widget displays the number of carts that have been **created** during the selected reporting period. Sometimes your customers might create a new cart and come back to it in the following days. In this case, the app will not update the date. It will still use the original creation date.

For example:
- Reporting period is set to today
- Customer added some products to the cart yesterday
- The very same customer returned to your store today and added some more products to the same cart

The app will show the cart as created yesterday, even though the customer updated it today.

For tech enthusiasts: This is because of the cart cookie in use by Shopify. It is valid for 14 days.

### Converted carts

The converted carts widget shows all the carts that have **converted** during the selected reporting period. The cart converts when there is a successful checkout associated with it.

### Conversion rate

Conversion rate widget displays **percentage of carts that resulted in a successful sale** during the selected reporting period.

### Average number of items

Average # of items widgets shows the average number of items (not products) that your customers added to their carts during the selected reporting period.

For example:
- Customer added 2 items of product A
- Later the customer added 1 item of product B
- In this example there are 3 items in the cart

### Carts list

List of all the opened carts during the selected reporting period is available in the carts list table. This table shows basic information about each of the carts (depends on the device you are using - mobile version of the app does not show all the information):
- Did the cart convert or not?
- List of the items that the customer added to the cart
- Value of the products in the cart
- Date and time of when the customer did the last changes
- Was the cart created as part of the Accelerated checkout? (Only available to our customers on a **Basic plan**)
- Button to mute the cart (Only available to our customers on a **Basic plan**)
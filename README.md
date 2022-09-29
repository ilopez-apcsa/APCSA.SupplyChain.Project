# APCSA.SupplyChain.Project

## Preface

You are the new Software Development intern for a local area food-bank/pantry. Your high school job board had a listing, they needed someone who could program in Java. The internship is 3 weeks long.

## Introduction
Welcome to the Pacific Northwest Food Bank (PNWFB). We are super glad you are here!

We provide a incredibly important resource to the community, and our donors/supporters have high expectations to make sure their monies are well used.

But we have a problem.  Our inventory management software cannot give us proper reports/tools to help us plan the needs we have for the area.

This is where we need your help.

## Goal

We need three reports.  These reports we should be able to run quickly and be readable in Microsoft Excel.  Janet in purchasing, and Jeff in Finance will be your contacts to answer questions about this project.

### Inventory Availability Report
In this report we need to have the following as columns:

- Item
- Description
- On Hand Quantity
- To Ship Quantity
- To Receive Quantity
- Available Quantity

Available Quantity is a formula = (On Hand - To Ship + To Receive)


### Can Build Report
The purpose of the report is to look at the kits in our inventory system, and find how many we can build of each kit

In this report we need to know the following:

- Kit Item
- Description
- Max Buildable Quantity

### Purchase Now Report

This is a report that we will run periodically and it will tell us what we need to order today so it arrives 


### Forecast Report

This is a report where we see all of the daily inventory levels per part until exhaustion.

In this report we need the following:
- Item
- Description
- Date
- On Hand

## Data

### Items
- item_number = Item Number
- item_description = Item Description
- kit_flag = Denotes is a kit
- food_group = What food group the item is in
- weight_g = Item package weight in grams
- kcal = Calories per package
- protein_g = Protein per package in grams
- fat_g = Fat per package in grams
- carbs_g = Carbs per package in grams

### Inventory
- item_number = Item Number
- qty = Qty On hand

### Open Shipments

- shipment_number = Ship Number
- shipment_date = Expected Ship Date
- item_number = Item Number
- ship_qty = Qty to Ship

### Open Purchases

- purchase_number = Purchase Number
- expected_arrival_date = Expected Arrival Date
- item_number = Item Number
- purchase_qty = Purchase Qty

### Kit Items

- kit_item_number = Parent Item
- child_item_number = Child Item Number
- child_qty = Child Quantity in Kit

## Deliverables

- All reports should be readable in Microsoft Excel/Google Sheets/OpenOffice Sheets.
- The first row should include the title of the report.
- The second row should include the date of when the report was generated.
- The third row should be the report columns
- The fourth and subsequent rows should be the report data.


## FAQ

### Q: Question
A: Answer

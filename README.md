# Bike-Sales-Excel-dashboard
Dash Board Project of Bike sales using MS Excel.

## Preprocessing
### Step 1
- Created Worksheet - Avoid working on live data
- Apply Filter to columns 
- Overview of columns 
	- data types 
	- overall data
	- Null Values

### Step 2
- Removal of Duplicates 


- Multiple categories have the same labels
	- Gender and Married 
		- M = Male / Married
		- Expanded M in both to avoid ambiguity using
			- `find and replace`
			- `ifs ` formula used here.
### Step 3 
- Numerical Processing
	- Currency
	- Date

### Step 4 
- Text Processing
	- Casing
	- Null Values
	- Values and lengths

### Step 5 
- Grouping / Binning Numerical values
	- Ages
		- Age Groups Created using Ifs
	- Income groups
	- Etc

- Group categorical Variables
- Ordinal Scaling Categorical Variables

## Pivot tables
- New Worksheet Pivot Tables
- Generate Pivot Tables according to 
	1. Gender vs Purchase
	2. Commute Distance vs Purchase
	3. Age Group vs Purchase

## Generating Charts
- New Sheet - Charts
- Charts corresponding to Pivot tables made
- New Pie Charts made to Separate Age distribution among Age and Purchase

## Dashboard
- New Sheet Dashboard
- Edit Background
- Edit Title
- Edit Chart Titles

### Inserting Slicers

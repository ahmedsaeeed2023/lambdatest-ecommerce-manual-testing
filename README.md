# Manual Testing – LambdaTest E-Commerce Playground

## 📋 Overview
Manual functional testing project performed on the **Components** category page of the LambdaTest E-Commerce Playground (a public demo e-commerce site used for QA practice). The project covers test case design, execution, and bug reporting following a professional QA workflow.

**Site under test:** [LambdaTest E-Commerce Playground](https://ecommerce-playground.lambdatest.io/)

## 🎯 Objective
To evaluate the functionality, usability, and data integrity of the Components category page — including navigation, filters, product listings, cart, wishlist, and compare features — and to identify defects through structured manual testing.

## 🛠️ Tools & Techniques
- **Test Design Techniques:** Equivalence Partitioning, Boundary Value Analysis, Exploratory Testing
- **Documentation:** Excel-based Test Case Reports & Bug Reports
- **Environment:** Browser: Brave | OS: Windows 11

## 📊 Summary of Results
- **55+ test cases** designed and executed across 6 functional areas:
  - Header/Breadcrumb, Sub-Categories, Toolbar (Grid/List/Sort/Compare), Product Cards, Pagination, Filters, Left Sidebar
- **20 bugs** identified and reported, including:
  - **4 Critical** severity bugs (data integrity issues)
  - **11 High** severity bugs
  - **5 Medium** severity bugs

## 🐞 Notable Bugs Found
| Bug ID | Title | Severity |
|--------|-------|----------|
| BUG-SC-002 | All sub-categories display identical content regardless of selection | Critical |
| BUG-PC-001 | Product cards show duplicate products with mismatched names/images | Critical |
| BUG-FL-002 | Manufacturer filter returns products from unselected manufacturers | Critical |
| BUG-FL-008 | Discount and Rating filters are completely inactive | Critical |
| BUG-PC-005 | Quick View modal displays wrong product images/details | Critical |

Full details for all 20 bugs are available in the [Bug Report](./bug-reports/Bug_Report_Component_Page.xlsx).

## 📁 Repository Contents

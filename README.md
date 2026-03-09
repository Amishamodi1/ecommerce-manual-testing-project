ecommerce-manual-testing-project – Amisha Modi
Manual Testing | API Testing

📌 About Me

Hi, I'm Amisha Modi — a Software Test Engineer with 4+ years of experience in Manual, API, and Automation Testing.
I specialize in ensuring software quality through comprehensive test planning, execution, defect analysis, and API validation.
This portfolio demonstrates my real-world QA testing work including test cases, bug reports, RTM, and API testing.

Application: OpenCart E-Commerce Platform  
Testing Type: Manual Testing + API Testing  
Test Duration: 7 Days  
Modules Tested: 14

📂 Portfolio Files

AmishaModi-QA-Portfolio/
│
├── 01_Test_Plan/                # Master test strategy document
├── 02_Test_Scenarios/           # High-level test scenarios by module
├── 03_Test_Cases/               # 267 detailed test cases with actual results
├── 04_Bug_Report/               # 14 real bugs with severity/priority
├── 05_Test_Summary/              # Final test execution summary report
├── 06_RTM/                       # Requirements Traceability Matrix
├── 08_API_Testing/               # Postman collection with 37 API tests
└── README.md                     # You are here!


📊 Key Metrics - Manual Testing

Metric	                Value
Total Test Cases	    267
Test Coverage	        93.7% (59/63 requirements)
Bugs Found	            14 (2 Critical, 6 High, 6 Medium)
Pass Rate	            90.6%
Testing Duration	    7 Days
Modules Covered	        14
Browsers Tested	        Chrome, Firefox, Safari, Edge
Devices Tested	        Desktop, Laptop, Tablet, Mobile


🐛 Top Bugs Found

Bug ID	  Module	           Issue	                                             Severity	             Status
BUG-009	  Cart	               Tax calculation uses 8% instead of 10%	             🔴 Critical	      In Progress
BUG-012	  Security	           No rate limiting on login attempts	                 🔴 Critical	      Fixed
BUG-002	  User Account	       Login with empty fields submits without validation	 🟠 High	          In Progress
BUG-003	  User Account	       Email changed without verification	                 🟠 High	          Open
BUG-008	  Product & Catalog	   Product comparison feature completely broken	         🟠 High	          Open
BUG-014	  Security	Session    cookie missing Secure flag	                         🟠 High	          In Progress


📊 API Testing Results

Metric	                Value
Total API Tests	        37
Passed	                37
Pass Rate	            100%
Methods Tested	        GET, POST, PUT, PATCH, DELETE
Endpoints Tested	    11
Avg Response Time	    1646 ms


Sample API Test Script

```javascript
pm.test('All users have valid email format', function() {
    var jsonData = pm.response.json();
    var emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    jsonData.forEach(function(user) {
        pm.expect(user.email).to.match(emailRegex);
    });
});

📂 Module-wise Test Coverage

Module	              Test Cases	Pass %	      Key Features Tested
User Account	      29	        86%	          Registration, Login, Password, Profile, Social Login
Product & Catalog	  45	        84%	          Categories, Search, Filters, Details, Reviews, Wishlist
Cart & Checkout	      36	        92%	          Add/Remove, Price Calc, Guest Checkout, Payment
Order & Payment	      35	        100%	      Order Placement, History, Returns, Refunds
Tax & Shipping	      22	        100%	      Tax Calc, Shipping Methods, VAT, Address Validation
Inventory	          16	        100%	      Stock Deduction, Out-of-Stock, Backorders
Admin & Roles	      32	        100%	      Product/Order Management, Role-based Access
Reports	              16	        100%	      Sales Reports, Export, Filters
Notifications	      11	        100%	      Order Emails, Password Reset, Shipping Updates
Promotions	          14	        100%	      Coupons, Discounts, BOGO
Security	          11	        73%	          Rate Limiting, Session Security, Access Control


🛠️ Tools & Technologies

Category	          Tools
Test Management	      Excel, Google Sheets
API Testing	          Postman, JSONPlaceholder
Bug Tracking	      GitHub Issues
Documentation	      Microsoft Word, Markdown
Screen Capture	      ShareX, Lightshot
Cross-Browser	      Chrome, Firefox, Safari, Edge
Version Control	      Git, GitHub


## 📂 Portfolio Files

📄 [Test Plan](./01_Test_Plan/Test_Plan.docx)

📊 [Test Scenarios](./02_Test_Scenarios/Test_Scenarios.xlsx)

✅ [Test Cases](./03_Test_Cases/Test_Cases.xlsx)

🐛 [Bug Reports](./05_Bug_Report/Bug_Report.xlsx)

📈 [Test Summary](./06_Summary_Report/Summary_Report.docx)

🔗 [RTM](./04_RTM/RTM.xlsx)

🔌 [API Testing Collection](./07_API_Testing/Amisha_Modi_API_Testing_Portfolio.json)

📑 [API Test Results](./07_API_Testing/Amisha_Modi_API_Test_Results.pdf)

📬 Contact

Email: amishamodi770@gmail.com
LinkedIn: https://linkedin.com/in/amisha-modi-0bb29a115


⭐ If you find this portfolio helpful, consider giving it a star!






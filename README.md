[issues.csv](https://github.com/user-attachments/files/25486196/issues.csv)This github repo is to showcase the project's I've done with Socia. 

Attached here is the link for the revised User Interface of Citiworks as instructed by Sir Jason. 

Design Link: https://www.figma.com/design/IV53CtPl3yJbIYPKlfc0LC/Internship?node-id=0-1  
Prototype Link: https://www.figma.com/proto/IV53CtPl3yJbIYPKlfc0LC/Internship?page-id=0%3A1&node-id=2003-12903&p=f&viewport=-7834%2C-12%2C0.66&t=j1YiwRicfTjCmoXn-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=2003%3A10142
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7f800db9-610b-4a85-a0fb-1f8592181550" />


Attached below is the link for my UI designing practice. My subject is KCO.

Design Link: https://www.figma.com/design/IV53CtPl3yJbIYPKlfc0LC/Internship?node-id=2159-5079  
Prototype Link: https://www.figma.com/proto/IV53CtPl3yJbIYPKlfc0LC/Internship?page-id=2159%3A5079&node-id=2165-5079&p=f&viewport=561%2C121%2C0.16&t=l0uAPsGNgat83yOi-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=2165%3A5079
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be3b32bc-54cc-4efc-b9be-67a9ae303052" />

QA Testing - February 23, 2026
Perfromed Manual QA Testing on APC-System
Detailed QA Report Attached: 
[Uploading issue#,Tracker,Status,Priority,Subject,Assignee,Updated,Description,Last notes
1080,Support,New,Normal,"Overlapping text and icon in List of Distributor ""Account Status""","",02/23/2026 01:30 PM,"In the List of Distributor module, the ?Account Status? column displays overlapping text and icon elements causing UI distortion and readability issues.

Steps to Reproduce:
1. Login as Admin
2. Navigate to Distributor List
3. Click List of Distributor
4. Observe Account Status button

Actual Result:
The text overlaps with the status icon.
The alignment appears compressed or stacked incorrectly.
UI becomes unclear and unprofessional in appearance.

Expected Result:
The status icon and text should be properly aligned (horizontally centered or evenly spaced).
No overlapping should occur regardless of screen size or resolution.
The layout should remain consistent across different browsers and devices.

![](clipboard-202602232130-dzhpz.png)
",""
1078,Bug,New,Normal,Admin - My Profile and Account displays same interface,"",02/23/2026 01:19 PM,"When accessing My Profile and Account under the Admin Quick Menu (three dots), both options display the same interface instead of showing their respective pages.

Steps to Reproduce:
1. Login as Admin
2. Navigate to three dots button 
3. Click either My Profile or Account
4. Observe behavior

Actual Result:
Both menu options load the identical interface/page.

Expected Result:
My Profile should display personal information (e.g., name, role, contact details, profile photo).
Account should display account-related settings (e.g., username, email, password settings, security preferences).

Expected Result:

![](clipboard-202602232115-4m7tn.png)
![](clipboard-202602232115-fokzx.png)
",""
1075,Bug,New,Normal,Remember Me function when signing in not working,"",02/23/2026 01:05 PM,"","The ?Remember Me? option on the Sign-In page does not function as expected. When selected, the system does not retain the user?s login session or credentials after logging out or refreshing the page.

Steps to Reproduce:
1. Access as Admin
2. Enter Email and Password
3. Click Remember Me
4. click Sign in button
5. Logout again
6. Observe behaviour

Actual Result:
User is not remembered.
Login credentials or session are not retained.
User is required to log in again despite selecting ?Remember Me.?

Expected Result:
When ?Remember Me? is selected, the system should retain the user session according to defined security policy.
User should remain logged in or credentials should be remembered for future visits (based on system design).

![](clipboard-202602232102-h10lc.png)
"
1074,Bug,New,Normal,Admin Quick Menu (My Profile and Settings) Not Working,"",02/23/2026 12:57 PM,"The Admin Quick Menu, specifically the ?My Profile? and ?Settings? options, is not functioning when clicked. Users are unable to access their profile information or system settings.

Steps to Reproduce:
1. Login as Admin
2. Click on Admin Quick menu
3. Select My Profile or Settings
4. Observe behavior

Actual Result:
Clicking My Profile produces no response / no redirection.
Clicking Settings produces no response / no redirection.
No error message is displayed.

Expected Result:
Clicking My Profile should redirect to the Admin profile page.
Clicking Settings should redirect to the system settings page.
The menu should function immediately without delay.

![](clipboard-202602232055-9wyou.png)
",""
1073,Bug,New,Normal,View All Notification Function Not Working,"",02/23/2026 12:48 PM,"The ?View All Notification? option is not functioning when clicked. Users are unable to access the full list of notifications.

Steps to reproduce:
1. Login as Admin
2. Navigate to Notification Icon on the upper part
3. Click View All Notification below
4. Observe behavior

Actual Result:
Clicking ?View All Notification? produces no action / no redirection.
The full notification list is not displayed.
No error message is shown.

Expected Result:
Clicking ?View All Notification? should redirect to a page displaying all notifications.
Users should be able to view complete notification history.
The function should respond immediately without delay.

![](clipboard-202602232046-zww5g.png)
",""
1072,Support,New,Normal,Double X button display when a distributor is selected,"",02/23/2026 12:37 PM,"When selecting a distributor from the list, two (2) ?X? buttons appear instead of one.
The duplicate ?X? button may cause confusion regarding which button should be used to remove or close the selected distributor.

Steps to Reproduce: 
1. Login as Admin
2. Navigate to Distributor List
3. Select List of Distributor
4. Select a Distributor
5. Observe the X button on the upper right side instead of one

Actual Result:
Two ?X? (remove/close) buttons are visible upon selecting a distributor.
UI appears duplicated or overlapping.

Expected Result:
Only one ?X? button should be displayed for removing or deselecting the distributor.
Interface should remain clean and consistent.

![](clipboard-202602232034-yqqx8.png)
",""
1070,Bug,New,Normal,Current Stock Update delay under Replenishment - Purpose (Lost),"",02/23/2026 12:30 PM,"There is a significant delay in stock updates under the Replenishment module
After replenishing stock, the updated quantity does not reflect immediately.
It takes approximately 1-2 minutes before the stock count updates in the system.

Steps to Reproduce:
1. Login as Admin
2. Navigate to the 3-dot menu on the uper right corner
3. Select replenishment
4. Click the Replenish + button
5. Select a product, observe stock, and then click Next
6. On the purpose, select Lost. Direction, OUT
7. Enter desired quantity to be deducted
8. Fill other required fields, then Next
9. Drop Image
10. Submit
11. Observe Quantity
12. Wait for a minute or two
13. See updated current stock

Actual Result:
The stock quantity does not update immediately.
The system reflects the updated quantity only after 1-2 minutes.

Expected Result:
Stock quantity should update instantly or within a few seconds after replenishment is confirmed.
The updated stock value should reflect in real time across relevant modules (Inventory List, Packages, etc.).

![](clipboard-202602232007-obuhu.png)
![](clipboard-202602232011-mlfke.png)
![](clipboard-202602232016-gawyi.png)
",""
1067,Bug,New,Normal,Admin - Package under Inventory and Logistics: ctrl F search inconsistent,"",02/23/2026 12:02 PM,"The search functionality in the Package List under Inventory & Logistics works correctly when using the search panel, but the Ctrl+F browser search command does not consistently highlight some items. 
Manual search via the search panel displays all matching items correctly.
Ctrl+F works for some items but fails to locate others in the package list.

Steps to Reproduce:
1. Log in as Admin
2. Navigate to Inventory & Logistics
3. Select Package
4. Type an item name in the search panel, the correct package appears
5. Press Ctrl+F and type the same item name
6. Observe that some items are not highlighted or found, even though they exist in the list

Actual Result:
Manual search works correctly for all items.
Ctrl+F only finds some items in the package list.
Items that are not visible to Ctrl+F may still exist in the list.
Inconsistent behavior between manual search and browser search.

Expected Result:
Ctrl+F should be able to locate all items in the package list, just like the search panel.
Search behavior should be consistent across manual input and keyboard shortcuts.
Users should be able to quickly find any package without missing results.


![](clipboard-202602232001-vor95.png)
![](clipboard-202602232001-0d1tm.png)
![](clipboard-202602232002-qsvvx.png)
",""
1065,Bug,New,Normal,Admin - Applications under Distributor List: ctrl-F command does not work correctly,"",02/23/2026 11:32 AM,"The search functionality in the Distributor Applications list does not respond correctly when using the Ctrl+F browser search command
When clicking the search panel manually and typing a customer name, the list of applicants displays correctly
When using Ctrl+F, the browser highlights product names instead of the distributor applicant names
Ctrl+F is intended for searching applicants, but it pulls unrelated data (products), leading to confusion.

Steps to Reproduce:
1. Log in as admin
2. Navigate to Distributor list
3. Select Application
4. Click inside the search panel and manually type a customer name. The list of applicants displays correctly
5. Press Ctrl+F and type the same customer name.
6. Observe that the browser highlights product names instead of applicant names.

Actual Results:
Ctrl+F does not search the applicant list.
Browser highlights unrelated product data.
The search functionality is inconsistent between manual search and Ctrl+F.

Expected Results:
Ctrl+F should focus on the applicant list and highlight matching names.
Manual search and browser search behavior should be consistent.
Users should be able to quickly locate applicant names using standard search methods.

![](clipboard-202602231926-vrs8p.png)
![](clipboard-202602231927-ni0lv.png)
",""
1064,Bug,New,Normal,Admin - Applications under Distributor List Status Filter Not Accurate and Not Working,"",02/23/2026 11:19 AM,"The Status Filter for distributor applications in the Admin panel is not working correctly.
Status filter options are All, Processing, Completed, and Cancelled.
All applications in the list have the status Pending, which is not included in the filter options.
Selecting any of the four filter options results in a 10?20 second delay, after which the application list disappears.
This behavior occurs for all filter options, making it impossible for administrators to filter by status effectively.

Steps to Reproduce:
1. Log in as Admin
2. Navigate to Distributor List
3. Select Applications
4. Observe that all applications have Pending status
5. Click the Status Filter dropdown and select All, Processing, Completed, or Cancelled.
6. Wait 10?20 seconds ? observe that the list disappears instead of displaying filtered results.

Actual Result:
Status filter options do not match the actual status values in the list.
Applying any filter causes a long delay (10?20 seconds).
After the delay, the application list disappears entirely.

Expected Result:
Status filter options should accurately reflect the actual statuses of applications (including Pending).
Selecting a status filter should immediately display applications with the selected status.
The list should not disappear after applying a filter.
Filtering functionality should be fast and responsive.


![](clipboard-202602231918-ervth.png)
![](clipboard-202602231918-lafjo.png)
![](clipboard-202602231918-7mid9.png)
![](clipboard-202602231919-dycjj.png)
![](clipboard-202602231919-akxmw.png)
",""
1060,Bug,New,Normal,Admin ? Applications under Distributor List Date Range Filter Not Working,"",02/23/2026 11:03 AM,"The date range filter for distributor applications in the Admin panel is not functioning correctly and exhibits significant delay.
Selecting Today does not filter today's application. Selecting This Week does not filter applications to the current week. Selecting This Month does not filter applications to the current month. 
When any filter is applied (Today, This Week, This Month), there's a 20-30 second delay before the list updates.
After the delay, the list disappears instead of showing filtered results
This prevents administrators from efficiently reviewing applications based on time period.

Steps to Reproduce
1. Log in as Admin
2. Navigate to Distributor List
3. Select Applications
4. Observe all listed applications
5. Apply date range filter (today, this week, this month) - Observe the delay and disappearance of the list;

Actual Result:
Date range filter do not display correct applications
Each filter takes 20-30 seconds to respond
After the delay, the application list disappears

Expected Result:
Today filter should only display all the applications made today
This week filter should display all the applications made this week
This month filter should display all the applications made this month
Date filter should update immediately without significant delay

![](clipboard-202602231900-vw6pt.png)
![](clipboard-202602231901-0kwgu.png)
![](clipboard-202602231901-gkhb0.png)
![](clipboard-202602231901-ug3fz.png)
![](clipboard-202602231902-f9krp.png)
",""
1055,Bug,New,Normal,Admin - List of Distributors Status Filter Not Working,"",02/23/2026 10:23 AM,"Status filter in the Admin List of Distributors does not filter records correctly. 
All distributors in the list have an Inactive status
Filtering by inactive shows no results
Filtering by active incorrectly displays all distributors with inactive status

Steps to Reproduce:
1. Log in as Admin
2. Navigate to Distributor List
3. Under Distributor List, select List of Distributor
4. Observe that all listed distributors have Inactive status
5. Apply the status filter to Inactive
6. Observe that no records are displayed
7. Apply the status filter to Active
8. Observe that all distributors that are inactive are displayed

Actual Result:
Status filter does not return correct results
Inactive distributors disappear when filtering by Inactive
Active filter incorrectly shows inactive records

Expected Result:
Filtering by Inactive should only show inactive distributors
Filtering by Active should only show active distributors
Filter logic should correctly match the status field


![](clipboard-202602231815-4s2oq.png)
![](clipboard-202602231815-w7khb.png)
![](clipboard-202602231816-e7fqn.png)
",""
1053,Bug,New,Normal,Learn button has no function on Become a Distributor/Seller interface,"",02/23/2026 08:59 AM,"On the Become a Distributor/Seller interface, the Learn button does not perform any action when clicked. Users cannot access additional information or guidance intended for this button.

Steps to Reproduce:
1. Open the site
2. Click either Become a Distributor or Seller
3. Click Learn button
4. Observe behavior

Actual Outcome:
Clicking the button produces no response

Expected Outcome:
Clicking the learn button should open the relevant content like for eg a guide page
![](clipboard-202602231651-f2qlp.png)
",""
1051,Bug,New,Normal,Distributor Registration form fields accept invalid input violating alphabetical and alphanumeric rules,"",02/23/2026 08:44 AM,"Form has multiple fields with different expected input types, but validation is not enforced correctly.

Steps to Reproduce:
1. Visit Site
2. Click Become a Distributor
3. Click Start Now Button
4. In supposedly-alphabetical-only fields, enter numeric values and/or special characters
5. In supposedly-alphanumeric/numeric-only fields, enter special characters
7. Click Next button until you reach the Submit Registration button
8. Click Submit Registration
9. Notice that it accepts invalid inputs

Actual Result:
Alphabetical-only fields accepts numbers and special characters
Alphanumeric/numeric fields accept special characters
Form submission is allowed despite invalid input

Expected Result:
Alphabetical-only fields must restrict input to letters
Alphanumeric/numeric fields must allow letters and numbers only
Form submission should fail with a validation message

![](clipboard-202602231619-rnlh4.png)
![](clipboard-202602231622-s3wa0.png)
![](clipboard-202602231624-dx390.png)
![](clipboard-202602231624-0bctd.png)
![](clipboard-202602231624-2869u.png)
![](clipboard-202602231624-ixojh.png)
",""
1047,Bug,New,Normal,"Suggested Product below are not clickable and displays ""Product not found"" error","",02/23/2026 08:14 AM,"When clicking items under the Suggested Products section, the system displays a notification in the upper right corner saying Product Not Found. The user isn't able to access the selected product page

Steps to Reproduce
1. Access the site
2. Sign In
3. Visit Shop
4. Select a product
5. Scroll down until you reach the Suggested Products section
6. Select a product
7. Observe behavior

Actual Result:
A pop up message appears on the upper right side saying ""Product not Found""
The user is not redirected to the selected product page
The suggested product link is broken or invalid

Expected Result:
Clickinig a suggested product should redirect the user to the correct product detail page
No error message should appear if the productr exists in the database

![](clipboard-202602231605-p4l9i.png)
",""
1045,Bug,New,Normal,Purchase button disabled for some products despite sufficient stocks,"",02/23/2026 08:02 AM,"Some product display sufficient stock availability but its Buy Product button is disabled. This prevents user to purchase items that are available. 

Steps to Reproduce:
1. Open the site
2. Sign Up
3. Click Visit Shop
4. Select a product
5. Observe that some products have an enabled purchase button, while others have disabled button despite the availablity of stocks
6. Attempt to click the disabled button

Actual Result:
Buy Product button is disabled for some products even though stock quantity indicates its availability
Users are unable to proceed with purchasing those products

Expected Result:
If stock quantity is greater than zero, Buy Product button should be enabled
Button state should dynamically reflect actual inventory data

![](clipboard-202602231553-cxwir.png)
![](clipboard-202602231553-p4h9v.png)
",""
1040,Bug,New,Normal,Error Handler on Sign Up Input Fields,"",02/23/2026 07:32 AM,"Fields such as Given Name and Last Name accepts numeric values. These fields should only allow alphabetic characters and valid name symbols. 
Phone number field has no maximum length validation

Steps to Reproduce:
1. Open site
2. Click Sign-Up
3. Input numbers on given and last name fields. 
4. Fill email, password, confirm password
5. Continuously enter numeric character exceeding a reasonable phone number length. 
6. Agree to terms and conditions
7. Click sign up button

Actual Result:
System accepts numeric values on given name and last name fields
Phone number fields allows unlimited numeric input without restriction
Form successfully proceeds/submits despite inivalid name format and excessive phone number. 

Expected Result:
Given name and last name fields should only accept alphabetic characters and valid symbols
The system should display validation error when numeric values are entered in name fields
Phone number field should have a defined maximum fields
System should prevent submission if validation rules are not met



![](clipboard-202602231516-vwyhm.png)
![](clipboard-202602231517-5irxi.png)
",""
1036,Bug,New,Normal,Reset Password does not proceed on Step 2 and 3,"",02/23/2026 07:01 AM,"When user clicks the Reset Password, enter his/her email, then click Send Reset Code button, it will send a password reset verification on the email entered. Upon sending, it should proceed to step 2. In this case, it doesn't proceed to step 2, it stays on step 1 only. 

Steps to Reproduce:
1. Sign In
2. Enter email
3. Click forgot password
4. Enter email again
5. Send reset code
6. Check email
7. Return to website
8. Observe behavior

Actual Result:
After receiving password reset verification, then going back to the site, it does not proceed on Step 2. 
Email entered is still on the input field, and still on step 1.

Expected Result:
After receiving password reset verification, and returning to site, it should proceed on Step 2 (Verification), not stick on the Step 1 since password reset verification is done. User should be able to input the verification code. Then proceed to Step 3. 


![](clipboard-202602231450-ltdmf.png)
![](clipboard-202602231451-rjotf.png)
![](clipboard-202602231451-cvtlo.png)
",""
1032,Bug,New,Normal,"""Remember Me"" Function in Sign In Not Working ","",02/23/2026 06:44 AM,"When a user log-in and enter his/her email and password then click the ""Remember Me"" function, upon logging out, the email and password isn't visible on the field. 
Clicking it does not perform any action. 

Steps to Reproduce:
Sign-in 
Enter email and password
Click ""Remember Me""
Sign-in
Logout again
Email and Password fields still empty

Actual Result:
Email and Password fields are still empty. Remember Me function does not serve its purpose.

Expected Result:
Upon logging in and entering email and password, then clicking the Remember Me checkbox, when you log out, it's suppose to save the input on fields. 
![](clipboard-202602231430-ukngx.png)
","![](clipboard-202602231444-8n3tj.png)
"
s.csv…]()

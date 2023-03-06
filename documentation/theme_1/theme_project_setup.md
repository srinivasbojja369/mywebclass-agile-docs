# Theme 1.0: Project Setup
## Overview
Our objective is to establish a highly visible web presence using lean and agile principles to quickly and effectively
develop a strong foundation for our web project. By completing the initiatives outlined in this theme, we can establish a
solid foundation that ensures our web page meets our business requirements throughout the life of the project, setting
us up for long-term success.

## Initiative(s)

* Build an Integrated Learning Experience
* Implement DevOps Practices
* Improve On-Page SEO for MyWebClass.org 

* Monitoring to continuously improve the quality of our project
  * Website analytics to collect data that can be used to continuously improve MyWebClass for our community members
  * Project metrics to continuously improve the management of the project

* Testing Required: Ombination of Automated and Manual Testing required.  

* Measuring it's effectiveness quantitatively:
  1. Number of active users on the website.
  2. Average session duration.
  3. Course completion rate.
  4. Deployment frequency.
  5. Organic search traffic.

## EPICS

* Implement Google Analytics for MyWebClass.org
* Enhance User Experience with Interactive Learning Tools

* Testing Required: Overall, a combination of manual and automated testing can help to ensure that the implementation of Google Analytics and the enhancement of the user experience with interactive learning tools are effective and provide value to users

* Measuring its effectiveness quantitatively:
  1. Traffic.
  2. Engagement
  3. Conversions
  4. User Feedback
  5. SEO Ranking

## USER STORY
* As a registered user, I want to be able to reset my password so that I can regain access to my account if I forget my password.
* As a customer, I want to be able to view my order history so that I can track my purchases and check the status of any pending orders.

* Testing Required :  it's recommended to use a combination of both automated and manual testing for testing these features to ensure comprehensive testing and better quality assurance

* Measuring its effectiveness quantitatively:
  1. To measure the effectiveness of the "Reset Password" feature, we can track the number of successful password resets and the time it takes for a user to reset their password. We can also track any errors or issues that users encounter while trying to reset their password.

  2. To measure the effectiveness of the "View Order History" feature, we can track the number of times this feature is accessed, the average time users spend on this page, and any feedback or complaints related to the feature. We can also track any errors or issues that users encounter while trying to access their order history

## Test plan for user stories
Test Plan for "Reset Password" User Story:

Verify that the "Forgot Password" link is visible on the login page.
Click on the "Forgot Password" link and verify that a form appears to input the email address associated with the account.
Enter a valid email address and click on the "Submit" button.
Verify that an email is sent to the user's email address with a link to reset the password.
Click on the reset password link in the email and verify that the user is redirected to a page where they can reset their password.
Enter a new password and verify that it meets the password criteria (if any).
Click on the "Submit" button to reset the password and verify that the user is redirected to the login page.
Log in using the new password to verify that it works.

Test Plan for "View Order History" User Story:

Log in to the MyWebClass.org website using a valid customer account.
Navigate to the account settings page and verify that there is a section for "Order History".
Click on the "Order History" link and verify that a list of the user's previous orders is displayed.
Click on a specific order to view its details and verify that the order information is correct and up-to-date.
Verify that the order status is displayed correctly and that any pending orders are clearly marked as such.
Test the pagination functionality to ensure that all orders are displayed and that users can navigate through them easily.
Verify that the order history page is responsive and that it looks good on different screen sizes and devices.


## Overall Testing:
The overall test plan for this project would involve both manual and automated testing to ensure that the MyWebClass.org website template provides a high-quality and effective learning experience for students.

Automated testing can be used to test the functionality of features such as the authentication system, course management system, feedback system, and progress tracking system. This can include unit tests and end-to-end tests using tools such as pytest and Playwright.

Manual testing can be used to test the overall usability and user experience of the website template. This can involve testing the navigation, user interface, and accessibility of the website, as well as conducting user testing to gather feedback from students, teachers, and administrators.

In addition to testing, the effectiveness of the website template can be measured quantitatively through Google Analytics tracking codes and goals. This can provide insight into how users are interacting with the website and help identify areas for improvement.

Overall, the test plan should ensure that the website template meets the needs of students, teachers, and administrators, provides an effective learning experience, and can be continuously improved and evolved over time.

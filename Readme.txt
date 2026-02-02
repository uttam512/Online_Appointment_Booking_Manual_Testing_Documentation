Online Appointment Booking System – Manual Testing

1. Project Objective

The objective of this project is to perform manual testing of an online appointment booking system to ensure that users can search services/doctors, book appointments, reschedule or cancel bookings, and manage appointments smoothly. 
The project focuses on validating business logic, user workflows, and system reliability.

2. Application Overview

The Online Appointment Booking System allows users to book appointments for services such as doctor consultations or other professional services. 
Users can select a service, choose an available date and time slot, confirm appointments, and manage their bookings through the application.

3. Scope of Testing
In Scope:

User Registration and Login

Service / Doctor Search

Appointment Booking

Date and Time Slot Selection

Appointment Confirmation

Appointment Rescheduling

Appointment Cancellation

Appointment History

User Profile


Out of Scope:

Backend database testing

Performance and load testing

Security penetration testing

Third-party notification integrations


4. User Roles

Guest User

Registered User


5. Testing Approach

The following manual testing activities were performed:

Understanding business requirements

Requirement analysis for each module

Test scenario creation

Test case design

Manual test execution

Defect reporting and tracking

Retesting and regression testing


6. Types of Testing Performed

Functional Testing

Smoke Testing

Sanity Testing

Regression Testing

UI Testing

Negative Testing


7. Test Environment

Application Type: Web Application

Browser: Google Chrome

Operating System: Windows

Test Data: Dummy user and appointment data


8. Entry and Exit Criteria

Entry Criteria:

Application is accessible

Test scenarios and test cases are prepared

Test environment is stable

Exit Criteria:

All planned test cases are executed

High and medium priority defects are logged

Test execution results are documented

9. Test Deliverables

Test Scenarios Document

Test Cases Document

Defect Report

Project Documentation

10. Sample Test Case

Test Case ID: TC_APPT_001

Test Scenario: Verify user is able to book an appointment with a valid date and available time slot

Preconditions:

User is registered and logged in

Service/Doctor is available

Test Steps:

Open the application

Login with valid credentials

Search for a service/doctor

Select an available date

Select an available time slot

Confirm the appointment

Expected Result:
Appointment should be booked successfully and confirmation should be displayed

Actual Result:
Appointment booked successfully and confirmation displayed

Status:
Pass

11. Defect Management Process

Defects identified during test execution were logged using MS Excel / Google Sheets. Each defect contained the following details:

Defect ID

Defect Summary

Module

Severity

Priority

Steps to Reproduce

Expected Result

Actual Result

Status


12. Sample Defects

Appointment slot still available after booking

User able to book appointment for past date

Appointment status not updated after cancellation


14. Conclusion

This project provided hands-on experience in testing a real-world appointment booking system. It helped in understanding business workflows, validating appointment logic, handling negative scenarios, and managing defects effectively.

15. Future Enhancements

Automation of appointment booking scenarios

Cross-browser testing

API testing for appointment and slot management

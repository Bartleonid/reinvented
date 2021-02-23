# Tech Quality Assurance services proposal to Perry Preston, Retail Reinvented from TechRozum inc.


## Table of Contents
[QA project for eCommerce web-applications](#QA-project-for-eCommerce-web-applications)
  - [Table of Contents](#table-of-contents)
  - [Objective](#objective)
  - [Tech Stack](#tech-stack)
  - [Types of testing](#types-of-testing)
  - [Levels of testing](#levels-of-testing)
  - [Magento specific testing](#magento-specific-testing)
  - [Roles and people](#roles-and-people)
  - [QA Strategy](#qa-strategy)
  - [Acсesses](#accesses)
  - [Acknowledgments](#acknowledgments)

## Objective
Assure high quality of a tested software for eCommerce Magento based web-applications using best QA manual/automation practices along with the best, optimal and most efficient QA process.

## Tech Stack
- [magento](https://magento.com/)
- [karate](https://github.com/intuit/karate/)
- [jmeter](https://jmeter.apache.org/)
- [test-rail](https://www.gurock.com/testrail/)
- [browserstack](https://www.browserstack.com/)

## Types of testing
 - functional
    * black-box
    * white-box where possible
 - non-functional
    * documentation
    * performance, load, stress
    * security
    * visual
    * design
    * usability
    * localization
    * compatibility testing
    * cross-browser testing (platform+browsers combinations, devices)

## Levels of testing
  - component testing
  - integration testing
  - system testing
  - acceptance testing


## Magento specific testing
  - Sign in/Login/Logout, Email verification testing
  - Checkout/place order testing 
      * valid/invalid cred cards testing
      * testing different types of payments (PayPal, Braintree PayPal, AuthNet and etc)
      * shiping address testing
      * redeem promo-codes testing
      * cart testing(amount/add/remove products)
  - Product page testing
      * product availability testing
      * simple product page testing
      * main product page testing
      * pagination testing
  - Admin testing
  - Filter testing
  - Third-parties integraion testing
  - Home page testing
  - My Account testing
  - Reviews testing
  - Banners testing
  - Support chat testing
  - Subscription testing
  - Add to Favorites testing
  - Discount testing

## Roles and people
- ***Leonid Bartshchuk*** - **QA Lead/Manager, Senior QA Automation Engineer**: leads/manages QA team, can help with Jira management and Development team, communicates with Retail Reinvented client and Development team. Provides QA Team with required accesses, tools. Defines QA strategy and technical approach. Develops and guides automation backend/frontend test framework development and test automation. Assists QA team with QA best practices and provides with recommendations in manual/automated testing. Can perform automated testing and CI configuration pipelines when free of leading/management tasks. 
- ***Yegor Basniev*** - **Senior QA Manual Engineer**: performs manual testing of a developed software. Detects, investigates, submitts defects into bug tracking system. Verifies fixed defects. Assure SDLC flow is being followed by Development and QA statuses updated accordingly. Makes test design and builds Traceability Matrix. Makes sure regression testing is provided timely and covers all main high priority functionality. Provides basic performance testing.
- ***Sam Slamakha*** - **Senior QA Automation (Performance) Engineer**: designs performance (stress, load) testing: automates backend/frontend regression test cases. Makes sure automated testing is performed timely, all tests are updated and fixed accordngly. Sets up CI like Jenkins and configure pipelines for the required types of regression and performance testing. Follow submitted automation found bugs and verifies them with runnning automated tests after PR is merged with a proper fix for a certain defect.

## QA Strategy
Stages:
  1. Requirements/Documentation (User Stories) review
  2. Communication with Business Analysts, Product Owners, Developers
  3. Jira flow review and updating with required QA statuses
  4. Composing Tracebility Matrix based on requirements
  5. Manual testing + test-design kick-off of high priority business cases test coverage using TestRail tool like Sig In. Checkout.
  6. API testing automation kick-off of high priority business use cases using Karate framework or JMeter
  7. Weekly QA review with Perry on QA team progress
  8. Jenkins pipeline set up with backend test job

## Accessess
  - Jira
  - Magento admin
  - TestRail
  - Confluence
  - Browserstack or Crossbrowsertesting if nesessary

## Acknowledgments

* Thanks to Perry Preston, Retail Reinvented and TechRozum QA team for the cooperation

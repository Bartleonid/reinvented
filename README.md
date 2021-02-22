# Tech Quality Assurance services proposal to Perry Preston, Retail Reinvented from TechRozum inc.


## Table of Contents
[QA project for eCommerce web-applications](#QA-project-for-eCommerce-web-applications)
  - [Table of Contents](#table-of-contents)
  - [Objective](#objective)
  - [Tech Stack](#tech-stack)
  - [Types of testing](#types-of-testing-to-be-provided)
  - [Levels of testing](#levels-of-testing-to-be-provided)
  - [Roles](#roles)
  - [Acсesses](#accesses)
  - [Acknowledgments](#acknowledgments)

## Objective
Provide high quality of a tested software for eCommerce Magento based web-applications using best QA manual/automation practices along with best, optimal and most efficient QA strategy.

## Tech Stack
- [magento](https://magento.com/)
- [karate](https://github.com/intuit/karate)
- [jmeter](https://jmeter.apache.org)

## Types of testing to be provided
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

## Levels of testing
  - component testing
  - integration testing
  - system testing
  - acceptance testing


## Magento specific testing
  - Sign in/Login/Logout testing
  - Checkout testing 
      * valid/invalid cred cards testing
      * testing types of different types of payments
      * shiping address testing
      * promo-codes
      * product-page testing
      * admin testing
      * product availability testing
      * third-parties integraion testing
  - 

## Roles
- **QA Lead/Manager, Senior QA Automation Engineer**: leads/manages QA team, can help with Jira management and Development team, communicates with Retail Reinvented client and Development team. Provides QA Team with required accesses, tools. Defines QA strategy and technical approach. Develops and guides automation backend/frontend test framework development. 
- **Senior QA Manual Engineer**: performs manual testing of a developed software. Detects, investigates, submitts defects into bug tracking system. Vefiies fixed defects. Assure SDLC flow is being followed by Development and QA statuses updated accordingly. Makes test design and builds Traceability Matrix. Makes sure regression testing is provided timely and covers all main high priority functionality. Provides basic performance testing.
- **Senior QA Automation (Performance) Engineer**: design performance (stress, load) testing: automates backend/frontend regression test cases. Makes sure automated testing is performed timely, all tests are updated and fixed accordngly. Sets up CI like Jenkins and configure pipelines for the required types of regression and performance testing. Follow submitted automation found bugs and verifies them after merged PR with proper fix for a ertain defect. 


## Manual testing responsibilities
At the start of the work, manual testing is used for covering main the application functionality by test cases that can be base for automation testing deploying. When automation is in progress, manual testing is optimal to test in parallel features without automation or if it will be necessary to verify the results of the autotests. With using of manual and auto testing results traceability matrix can be created for a detailed analysis of test coverage and risk management. As an element of manual testing, the acquisition of testing metrics with reporting about main testing achievements will be provided.  

## Accessess


## Acknowledgments

* Thanks to Perry Preston from Retail Reinvented and TechRozum QA team

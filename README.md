# Project Title

`The Cooper Test Challenge`

Craft Academy - week 7 out of 12

May 2019

# Problem Statement

We have a client request to build a fitness tracking application. The idea is that the app will allow users to track their condition using a specific test called The Cooper Test.

The challenge is to build a software solution that will make it possible not to only make the calculation, but to record the data over time. Another requirement is that the app should have functionality that presents historical data of tests if a user has saved any historical data.

# History

The Cooper Test (aka The 12-minute run) was developed by Dr. Ken Cooper in 1968 as an easy way to measure aerobic fitness and provide an estimate of VO2 max for military personnel. The Cooper test, as it's also known, is still used today as a field test for determining aerobic fitness.

Dr. Cooper found that there is a very high correlation between the distance someone can run (or walk) in 12 minutes and their VO2 max value, which measures the efficiency with which someone can use oxygen while exercising. This test is still one of the basic fitness tests used by the military. It is also used by many coaches and trainers to determine cardiovascular fitness and track fitness over time. This simple test also allows you to compare your cardiovascular endurance with others of your age and gender.

# Getting Started

For the pusrposes of this project we built a backend API solution using Ruby on Rails and a frontend client solution using React. The repositories where the code is available are the following:
* **Leiter007** [API](https://github.com/leiter007/cooper_api), [Client]()
* **Raptorf1** [API](https://github.com/raptorf1/cooper_api), [Client]()

# Prerequisites

You must have `Ruby`, `Ruby on Rails`, `Node.js` & `Bundler` installed in your system to be able to view this app and run all feature, unit and acceptance tests. After forking the repository run `bundle install` so that you download all the gems used in the project.

# Installing

* To fire up the rails API server, first you will have to create and migrate the databases. To do that, you run in your terminal `rails db:create` and `rails db:migrate`. For the server to activate, run `rails server` in your terminal.
* To fire up the react client, run `npm start` in your terminal.

# Running the tests

* The API was unit tested using Rspec. To run the tests in your terminal use `bundle exec rspec`.
* The client was tested using Cypress and Enzyme. To run the acceptance tests of Cypress use `npm run cy:open`. To run the react component Enzyme tests use `npm run test`.

# Built With

* Ruby version 2.4.1
* Ruby on Rails version 5.2.0
* React

# Authors

* **Leiter007** - [GitHub](https://github.com/leiter007) - [Portfolio](https://felix-react-portfolio.netlify.com/)
* **Raptorf1** - [GitHub](https://github.com/raptorf1) - [Portfolio](https://gtomaras-portfolio.netlify.com/)

# License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.

# Acknowledgments

* [PurpleBooth](https://github.com/PurpleBooth) for this README template.

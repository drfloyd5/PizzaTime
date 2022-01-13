# PizzaTime
Small app to take pizza orders.

## Description

A small two or 3 page app for ordering pizzas.

- [PizzaTime](#pizzatime)
  - [Description](#description)
  - [Contributing Instructions](#contributing-instructions)
  - [Interview Expectations](#interview-expectations)
  - [Skillset Requirements](#skillset-requirements)
  - [Scenario](#scenario)
  - [Business Requirements](#business-requirements)
    - [Topping Management](#topping-management)
    - [Order Taking](#order-taking)
    - [Driver Page](#driver-page)
    - [Overall UI](#overall-ui)
  - [High Priority Deliverables](#high-priority-deliverables)

## Contributing Instructions
1. Clone the repo.
2. Share a minium your IDE in the meeting.
3. Raise a pull request with your changes.

## Interview Expectations
1. The development environment may be setup before the interview.
2. We are looking at your competence, coding style, how your thought process works. 
3. You may prepare as you see fit. However, we want to see you code. Please do not write a solution and then copy it by hand during the interview.
4. We will stay out of your way and not ask a bunch of question. Unless we think you are misunderstanding a requirement or are otherwise going a completely wrong direction.
5. Ask as many questions as you like.
6. A completed product is not required, but we should be able to tell what direction you are going and be able to extrapolate the rest of your approach.
7. Don't worry about making mistakes. It happens, we all know that. What is important is what is in the pull request.
8. We are not going to 100% watch you code the entire time. Unfortunately, we have other work we must also attend to. But we will keep the meeting window open on the 2nd monitor.
9. The Pizza Time! owner can be requested to join the meeting. (The part of the Pizza Time! owner will be played by one of the interviewers.)

## Skillset Requirements
1. Feel free to make assumptions about gaps in the requirements. If you do, please make a small note of your assumption. This will help us refine the project requirements.
2. Visual Studio or Visual Studio Code may be used.
3. IDE extensions are fine.
4. Googling is fine.
5. Backend coded in .NET 5 or 6
6. Front end coded with Angular 11
7.  Database access should be done with Entity Framework.
   1.  Using EF Core In-Memory Database Provider is fine. Optionally, The data may be persisted to any backing database EF can work with.
   2.  In any case reference data should be present at app start.
8.  ??? Google Material ???
9.  The visual aesthetic of the website is of minor importance. However:
   3. The overall look should be consistent.
   4. Form labels and controls should be reasonably placed.
  
## Scenario

A small restaurant named Pizza Time! is growing fast. They now require an app for employees to take orders over the phone. The restaurant is famous for their pizza crust, so they only use one kind of dough and only sell one size of pizza. Pizza Time! also takes pride in using locally sourced toppings. Sometimes a topping is unavailable for the day because of supply issues. However sometimes a special toping is available for a day, based on what the owner finds at the market.

Pizza Time! approached our sales department for a solution. We don't currently sell a product Pizza Time! can use. But the sales people sold them a promise. The president of our company has asked us to go ahead and produce a solution. Pizza Time! is patient as long as they regularly see progress.

## Business Requirements

### Topping Management
* Pizza Time needs a way to manage what pizza toppings they can use. Pizza Time! is only concerned with the name, availability to order, and the customer price of a topping.

* Some toppings cost more than other toppings.

* Some toppings can only be applied to the entire pizza.

* An employee must know the current secret password to manage the toppings.

### Order Taking
* Pizza Time! only takes phone orders. They do not allow walk-ins. Pizza Time! tracks orders by phone number.
 
* An order consists of the number of pizzas, 3 or less. Toppings, sometimes customers want different toppings on each half of a pizza. Pizzas can only be customized by halves; no quarter pizza customizations. Half a pizza topping costs half price.

* If the customer orders 5 toppings they get a 6th topping free.

* Sometimes customers call to complain they did not get the proper order. So any Pizza Time! employee must be able to look up previous orders based on phone number. In fact this is so important that every page must have the ability to look up a phone number an see the order without leaving the page.

* Pizza Time is considering doing online orders in the future.

### Driver Page
* Delivery drivers must be able to see what orders have been ordered. When a driver prepares to deliver the order they must "claim" the order.

* Sometimes the drivers make last minute changes so they should be able to change the name on the order. But a driver should not be able to "steal" an order. 

* Pizza Time! requires drivers to verify the pizzas are correct before delivery. There is no need to capture the verification because it is assume the driver who claimed the order, did the verification. The customer will complain if the order is wrong, so Pizza Time! will know the driver did not properly check the pizza.

### Overall UI
* Any employee can use the app from any screen in the restaurant. So it should be easy to switch from page to page.

* The drivers monitor is about 1.5 meters from the driver station where they use the application.

* A standard keyboard is always used. One of the 3 order taking stations uses a touchscreen with a standard keyboard. Pizza Time! has plenty of mice.

## High Priority Deliverables
1. Before the project can get started our company must give PizzaTime! some idea of what they are buying. A verbal description of the UI is acceptable.
2. Our boss wants to know when we can start the next project. He would like an estimate with plus or minus 25% accuracy for this product. He understands that it is impossible to estimate projects with 100% accuracy.




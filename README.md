# PizzaTime
_A small app to take pizza orders._

## Hello
Thank you for applying to our position. Choosing to work together is a two way street and neither of us need to waste time with a bad fit. This project is meant to get a sense of your development style; what kinds of questions you ask; What assumptions you make; and how well do we communicate. Of course your skills are also being evaluated. In turn, you get to evaluate us.

We are developers, we get it.

This is our first time using a coding exercise during our interview process. I will greatly appreciate any feedback you share about the process.

## Special Note

We are aware the interview duration is too short to accomplish the project. Please feel

## Description
A small two or 3 page app for ordering pizzas.

- [PizzaTime](#pizzatime)
  - [Hello](#hello)
  - [Special Note](#special-note)
  - [Description](#description)
  - [Contributing Instructions](#contributing-instructions)
    - [Before Interview](#before-interview)
    - [During Interview](#during-interview)
  - [Interview Expectations](#interview-expectations)
  - [Skill Set Requirements](#skill-set-requirements)
  - [Scenario](#scenario)
  - [Business Requirements](#business-requirements)
    - [Topping Management](#topping-management)
    - [Order Taking](#order-taking)
    - [Driver Page](#driver-page)
    - [Overall UI](#overall-ui)
  - [High Priority Deliverables](#high-priority-deliverables)

## Contributing Instructions

### Before Interview

1. Setup Development environment.
2. Clone the repo. 
4. Make a branch. Please include your name, job id*, and candidate id*, and whatever other text you like. (*if you know them.)
5. Code Solution.
5. Push branch.

### During Interview
1. Share desktop.
2. We will have a conversation about your code.
3. An additional requirement will be raised during the review. Some coding will be expected.

## Interview Expectations

1. We are looking at your competence, coding style, how your thought process works.
2. When we as for more coding, we will stay out of your way and not ask a bunch of question. Unless we think you are misunderstanding a requirement or are otherwise going a completely wrong direction.
3. Ask as many questions as you like.
4. A completed product is not required, but we should be able to tell what direction you are going and be able to extrapolate the rest of your approach.
5. We don't expect 100% production quality code. However please add TODO comments that you feel would be necessary for production quality code. Example:
```csharp
var f = File.ReadAllText("c:\\temp\\data.txt"); // TODO: catch exceptions and return default values. 
                                                // TODO: Remove hard coded filename.
```
8. Don't worry about making mistakes. It happens, we all know that. What is important is what is in the pull request.
9. We are not going to 100% watch you code the entire time. Unfortunately, we have other work we must also attend to. But we will keep the meeting window open on the 2nd monitor.

## Skill Set Requirements

1. Feel free to make assumptions about gaps in the requirements. If you do, please make a small note of your assumption. This will help us refine the project requirements.
2. Visual Studio or Visual Studio Code may be used. IDE extensions are fine.
5. Backend coded in .NET 5+
6. Front end coded with Angular 11+
7. Database access should be done with Entity Framework.
   1. Using EF Core In-Memory Database Provider is fine. Optionally, The data may be persisted to any backing database EF can work with.
   2. In any case reference data should be present at app start.
8. Feel free to use google or the rest of the internet.
9.  The visual aesthetic of the website is expected to be minimal.
   1. The overall look should be consistent.
   2. Form labels and controls should be reasonably placed.
   
  
## Scenario

A small restaurant named Pizza Time! is growing fast. They now require an app for employees to take orders over the phone. The restaurant is famous for their pizza crust, so they only use one kind of dough and only sell one size of pizza. Pizza Time! also takes pride in using locally sourced toppings. Sometimes a topping is unavailable for the day because of supply issues. However sometimes a special toping is available for a day, based on what the owner finds at the market.

Pizza Time! approached our department for a solution. We don't currently have a product Pizza Time! can use. The department lead feels this is an opportunity for the company to push into a new market. Pizza Time! pays for the development of a product that we can license to other small businesses.

Pizza Time! is eager to start using our app and demand a solid delivery date. Our department lead has negotiated a flexible delivery schedule in exchange for keeping them informed of our progress.

## Business Requirements
Special Note: These requirements were gathered by non-technical people.

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
1. Before the project can get started our company must give PizzaTime! some idea of what they are buying. A verbal description of the UI is acceptable. A picture of a hand drawn sketch is also fine.
2. Our boss wants to know when we can start the next project. He would like an estimate with plus or minus 25% accuracy for this product. He understands that it is impossible to estimate projects with 100% accuracy.




# [Course Registration Roster](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin)  <img alt="Static Badge" src="https://img.shields.io/badge/Last_commit-16/_9/_2023-green">

This is the 7th assignment of Complete Web Development Course of Programming Hero. Here I have given the answers of the questions.

## [Some Project Features](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin)

There are some features in this project. Here I have provided some of them:

- Add to Cart - There is a button in the courses' body named "select" by which we can add that course to the cart section. In the cart section, the selected course are shown as a list.

- Calculate credit - As a default, total 20 credits are given to a user for purchasing the courses and each course has a credit. After selecting a course, the amount of each course credit are deducted from the total credit. The credits which are consumed by a user are also calculated in cart section.

- Calculate total price - Each course has a price. The courses which are selected by a user have a total amount and that amount is calculated and shown in the cart section.

- Remove from Cart - There is a button beside each selected course and a user can remove that selected course by this feature.

## [Management of states in the project](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin)

First of all, I have created a state for storing the all courses' cards. Then by using useEffect hook, I have loaded the data from API and set the data to state. Then I have showed all course API data dynamically.

<p align="center">
  <img src="https://i.postimg.cc/Wb3RcKn3/state1.png" width="600" height="300">
</p>

Then, I have created another state for storing the selected course. Selected courses' are shown in the cart section dynamically by passing data to the component.

<p align="center">
  <img src="https://i.postimg.cc/fWmbTdCG/state2.png" width="600" height="100">
</p>

Next, there is a state for handling the total credit deduction and how many credits are left is shown in the cart section dynamically. The initial value is set 20 credits in this state. Then each selected card's course credit has been deducted from 'totalCredit' variable accordingly after selecting the cards.

<p align="center">
  <img src="https://i.postimg.cc/gc36BjwK/state3.png" width="550" height="100">
</p>

Again, there is a state for calculating the total course price and how much money has to be paid is shown in the cart dynamically. The initial value is set 0. Then each selected card's course price has been added to 'totalPrice' variable accordingly after selecting the cards.

<p align="center">
  <img src="https://i.ibb.co/yhnnj2s/state4.png" width="550" height="100">
</p>

Afterwards, I have created a state for handling the total credit consumed by a user and how many credits have been used is shown in the cart section dynamically. The initial value is set 0. Then the course credit has been added one by one after selecting the cards.

<p align="center">
  <img src="https://i.ibb.co/QnPBxrX/state5.png" width="550" height="100">
</p>

That's how I have managed the states of this project.

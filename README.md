# [Course Registration Roster](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin) [![Generic badge](https://img.shields.io/badge/Updated-Today-<COLOR>.svg)](https://shields.io/)

This is the 7th assignment of Complete Web Development Course of Programming Hero. Here I have given the answers of the questions.

## [Some Project Features](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin)

There are some features in this project. Here I have provided some of them:

- Add to Cart - There is a button in the courses' body named "select" by which we can add that course to the cart section. In the cart section, the selected course are shown as a list.

- Calculate credit - As a default, total 20 credits are given to a user for purchasing the courses and each course has a credit. After selecting a course, the amount of each course credit are deducted from the total credit. The credits which are consumed by a user are also calculated in cart section.

- Calculate total price - Each course has a price. The courses which are selected by a user have a total amount and that amount is calculated and shown in the cart section.

- Remove from Cart - There is a button beside each selected course and a user can remove that selected course by this feature.

## [Management of states in the project](https://github.com/programming-hero-web-course2/my-course-roster-NafizUddin)

First of all, I have created a state for storing the all courses' cards. Then by using useEffect hook, I have loaded the data from API and set the data to state.
<img src="[image.png](https://carbon.now.sh/?bg=rgba%28171%2C+184%2C+195%2C+1%29&t=seti&wt=none&l=auto&width=680&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false&code=const%2520%255BallCourse%252C%2520setAllCourse%255D%2520%253D%2520useState%28%255B%255D%29%253B%250A%250AuseEffect%28%28%29%2520%253D%253E%2520%257B%250A%2520%2520%2520%2520fetch%28%2522.%252Fdata.json%2522%29%250A%2520%2520%2520%2520%2520%2520.then%28%28res%29%2520%253D%253E%2520res.json%28%29%29%250A%2520%2520%2520%2520%2520%2520.then%28%28data%29%2520%253D%253E%2520setAllCourse%28data%29%29%253B%250A%2520%2520%257D%252C%2520%255B%255D%29%253B)https://carbon.now.sh/?bg=rgba%28171%2C+184%2C+195%2C+1%29&t=seti&wt=none&l=auto&width=680&ds=true&dsyoff=20px&dsblur=68px&wc=true&wa=true&pv=56px&ph=56px&ln=false&fl=1&fm=Hack&fs=14px&lh=133%25&si=false&es=2x&wm=false&code=const%2520%255BallCourse%252C%2520setAllCourse%255D%2520%253D%2520useState%28%255B%255D%29%253B%250A%250AuseEffect%28%28%29%2520%253D%253E%2520%257B%250A%2520%2520%2520%2520fetch%28%2522.%252Fdata.json%2522%29%250A%2520%2520%2520%2520%2520%2520.then%28%28res%29%2520%253D%253E%2520res.json%28%29%29%250A%2520%2520%2520%2520%2520%2520.then%28%28data%29%2520%253D%253E%2520setAllCourse%28data%29%29%253B%250A%2520%2520%257D%252C%2520%255B%255D%29%253B" width="200" height="100">


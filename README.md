# **Way-Farer**

## **Project description**

WayFarer is a public bus transportation booking service.

## **UI Required features**

- [Sign up.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/signup.html)
- [Sign in.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/signin.html)
- [Admin can create a trip.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/create_trip.html)
- [Admin can cancel a trip.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/admin/trip_del.html)
- [View all trips.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/index.html)
- [View a specific trip.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/trip.html)
- [Book a seat on a trip.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/book.html)
- [View all bookings.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/admin/index.html)
- [View all bookings by the user.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/bookings.html)

- [Delete a booking.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/booking.html)

# **Optional features**

- [Filter trips based on origin.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/index.html)
- [Filter trips based on destination.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/index.html)
- [Specify a seat number when making a booking.](https://OkelloAndrewPeters.github.io/Way-Farer/UI/book.html)

# **Technonlogies**

- **Express JS** - API development framework

- **Node** - run time environment for JavaScript
- **Mocha and Chai** - for testing
- **Eslint** - code analysis tool for identifying problematic patterns found in JavaScript code
- **Babel JS** - JavaScript compiler (**ES6** to **ES5**)

# **Requirements and Installation steps**

## **You need the following to be able to run the application**

[Node](https://nodejs.org/en/download/) a runtime environment for JavaScript

[Postman](https://www.getpostman.com/downloads/) to test the Api endpoints

[Visual studio code](https://code.visualstudio.com/download) for editing and running the app

## **Clone the project**

    - git clone https://github.com/OkelloAndrewPeters/Way-Farer.git
    - cd /Way-Farer
    - npm install (to install required dependencies)
    - npm run dev (to start the development server)

## **Testing**

    - npm run test

## **API endpoints**
`- POST /auth/signin - User Signin` 

`- POST /auth/signup - User to create an account` 

`- POST /trips - Create a trip`

`- GET /trips/<:trip-id> - Get a specific trip`

`- GET /trips - Get all trips.`

`- PATCH /trips/<:trip-id>/cancel - Cancel a trip`

`- GET /trips?origin=kigali -Filter trips based on origin.`

`- GET /trips?destination=kampala -Filter trips based on destination.`

`- POST /bookings - Book a seat on a trip`

`- GET /bookings - View all bookings`

`- DELETE /bookings/<:booking-id> - Delete a booking`

## **UI Templates**

[https://OkelloAndrewPeters.github.io/Way-Farer/UI/](https://OkelloAndrewPeters.github.io/Way-Farer/UI/)


# **Author**

## **Okello Andrew Peters**

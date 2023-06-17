# BookMyShow App - Low-Level Design Requirements

## Actors

1. User/Customer
2. Administrator/System
3. Theater Owner/Manager
4. Payment Gateway
5. Movie Distributors/Producers
6. SMS/Email Service Provider

## User/Customer Requirements:

- Register, create and authenticate user profile.
- Browse and search for movies by title, genre, language, or location.
- View movie details, including synopsis, cast, and crew information.
- Check theater locations, available showtimes, and seating availability.
- Select seats and book tickets for desired shows.
- Make secure online payments using different payment options.
- Receive booking confirmation and e-tickets via email or SMS.
- View past bookings, booking history, and upcoming shows.
- Rate and review movies and theater experiences.

## System Requirements:

- Secure login and authentication for administrators.
- Manage movie listings, including adding, editing, and removing movies.
- Maintain theater information, including seating capacity and layouts.
- Define show timings and ticket prices for different movies and theaters.
- Monitor and manage user reviews and ratings.
- Generate reports on ticket sales, revenue, and popular movies.

## Theater Owner/Manager Requirements:

- Register their theaters and provide necessary details.
- Add/modify theater show timings, seat availability, and prices.
- View and manage bookings for their theaters.
- Receive notifications of new bookings and cancellations.
- Monitor seat occupancy and availability in real-time.

## Payment Gateway Requirements:

- Provide secure payment processing capabilities.
- Support multiple payment methods, such as credit/debit cards, net banking, and mobile wallets.
- Integrate with the app to handle payment transactions seamlessly.

## Movie Distributors/Producers Requirements:

- Provide movie details, including titles, synopses, trailers, and cast information.
- Update movie show timings and schedules.
- Receive reports on ticket sales and revenue.

## SMS/Email Service Provider Requirements:

- Integrate with the app to send booking confirmations and updates to users.
- Ensure reliable and timely delivery of messages.

## SOLID Principles

Based on the provided requirements for the BookMyShow app, the following SOLID principles can be observed in the design:

1. **Single Responsibility Principle (SRP):**
   - Each actor has its own set of requirements, representing a single responsibility.
   - The User/Customer, Administrator, Theater Owner/Manager, Payment Gateway, Movie Distributors/Producers, and SMS/Email Service Provider requirements are clearly separated and focused on their specific roles.

2. **Open/Closed Principle (OCP):**
   - The requirements are stated in a way that allows for extension and addition of new features without modifying existing code.
   - For example, additional features or actors can be accommodated without changing the existing requirements for User/Customer, Administrator, or other stakeholders.

3. **Liskov Substitution Principle (LSP):**
   - The requirements do not explicitly mention inheritance or polymorphism, so the Liskov Substitution Principle does not have a direct application in this context.

4. **Interface Segregation Principle (ISP):**
   - The requirements do not explicitly mention interfaces or classes, so the Interface Segregation Principle does not have a direct application in this context.
   - However, the segregation of requirements based on actors can be seen as a form of interface segregation, where each actor's specific needs are addressed separately.

5. **Dependency Inversion Principle (DIP):**
   - The requirements do not explicitly mention dependencies or inversion of control, so the Dependency Inversion Principle does not have a direct application in this context.
   - However, it's important to consider dependency management and potential abstraction layers when implementing the requirements to ensure loose coupling and flexibility.



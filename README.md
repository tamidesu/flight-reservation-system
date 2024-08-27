# Flight Reservation System

## Overview

The Flight Reservation System (FRS) is a comprehensive solution designed to facilitate customers in booking, modifying, and canceling flights. It interacts with a central database containing information about available flights, seats, and customer profiles. Additionally, the system integrates with payment processing channels to ensure secure transactions and supports a loyalty program to enhance customer satisfaction.

## Authors

- Alzhan Temirlan

## Laboratory Work 1: Software Requirements Specification

### Description

The FRS enables customers to search for flights based on various criteria, book seats, and manage their reservations. It also allows customers to modify or cancel their bookings according to predefined rules. Integration with an existing loyalty program provides benefits like accumulating and redeeming points. The system includes an administrative module for managing flight schedules, seats, and customer support.

### Functional Requirements

1. **Search and Booking**: Customers can search for flights, select seats, and book flights. The system confirms bookings with a unique reference.
2. **Reservation Management**: Customers can modify or cancel their reservations.
3. **Payment Processing**: The system processes payments securely and generates electronic tickets.
4. **Loyalty Program Integration**: Customers can enroll in the loyalty program and manage their points.
5. **Notifications**: The system sends booking confirmations and updates.

### Non-Functional Requirements

1. **Security**: Compliance with industry standards for data protection, secure authentication mechanisms.
2. **Administrative Module**: Manage flight schedules, seat availability, and customer support.
3. **Reporting**: Generate reports on reservations, system usage, and transactions.

## Laboratory Work 2: Identifying Use Cases

### List of Actors

1. **Customer**: Interacts with the system for flight operations and loyalty program management.
2. **Administrator**: Manages flight schedules, reservations, and provides customer support.
3. **Loyalty Program**: Manages loyalty points.
4. **Payment Gateway**: Handles secure payment transactions.

### Key Use Cases

- **Customer**: Search for Flights, Book a Flight, Modify Reservation, Cancel Reservation, View Loyalty Points, etc.
- **System Administrator**: Manage User Accounts, Flight Information, Security Audits, etc.
- **Loyalty Program**: Track and Update Points, Send Promotional Offers.

## Laboratory Work 3: Software Life Cycle Modeling

### Models

1. **Waterfall Model**: Sequential phases suitable for well-defined projects.
2. **Agile Model**: Iterative approach for dynamic requirements and customer feedback.

### Summary

The Waterfall model's structured approach ensures thorough documentation, while Agile's flexibility supports rapid changes and continuous improvement.

## Laboratory Work 4: Analyze Architecture Diagrams

### View Types

- **Domain Models**: Shows connected concepts.
- **Use Case Diagram**: Details steps and actors.
- **Allocation View**: Deployment-related views.
- **Component Assembly**: Internal system components.

## Laboratory Work 5: Actors and Roles

### Key Roles

1. **Customer**: Interacts with the Reservation System.
2. **System Administrator**: Manages the system and supports customers.
3. **Loyalty Program**: Manages loyalty benefits.

## Laboratory Work 6 & 7: Creating UML Diagrams

- **Dynamic UML Diagrams**: Illustrate real-time interactions.
- **Class Diagram**: Depicts system classes and relationships.
- **Component Diagram**: Visualizes components and dependencies.
- **Deployment Diagram**: Shows system deployment across hardware.

## Laboratory Work 9: Choosing the Best Pattern

### Patterns Used

1. **Factory**: To create different types of flights.
2. **Singleton**: Ensures a single instance of the booking system.
3. **Composite**: Represents flights with varying seat types.
4. **Proxy**: Controls access to the booking system.
5. **Observer**: Notifies passengers about flight status changes.
6. **Strategy**: Implements different pricing strategies.

## Laboratory Work 10: Applying Architectural Styles

### Styles

1. **Layered Style**: Divides the system into presentation, business logic, and data access layers.
2. **Client-Server & N-Tier**: Structures the system with clients interacting with a server across multiple tiers.
3. **Pipe and Filter**: Uses independent filters to process flight search requests.

## Quality Concerns Addressed

1. **Security**: Enhanced with encryption and multi-factor authentication.
2. **Performance**: Optimized with load testing and efficient architecture.
3. **Scalability**: Ensured through modular design and robust architecture.

## Summary

The Flight Reservation System is designed to provide a seamless and secure experience for customers and administrators. By leveraging different software models, use case analysis, and design patterns, the system is built to handle complex flight operations while ensuring flexibility, security, and scalability. Regular updates and testing ensure that the system meets the evolving needs of its users and maintains high standards of service.

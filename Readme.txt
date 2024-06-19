Summary of OOP Concepts
Classes and Encapsulation: User and Post classes encapsulate properties and provide methods to access and modify these properties.
Inheritance: RegularUser, AdminUser, and GroupAdmin inherit from User and provide additional functionalities.
Interfaces: UserActions and AdminActions define methods that must be implemented by any class that implements these interfaces.
Polymorphism: Methods like performUserActions and performAdminActions can accept any object that implements UserActions or AdminActions, respectively, allowing for flexible and reusable code.
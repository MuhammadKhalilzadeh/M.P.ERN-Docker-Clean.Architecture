# (M + P) ERN, Docker, Clean Architecture for BlueWave Labs: VerifyWise

**A Suggestion for an Enterprise Application**

---

### Our Stacks, a combination of MERN and PERN

![Enterprise Application Diagram](./images/Mern%20+%20Pern.png)

---

#### What does MERN stands for?

MERN: MongoDB + Express.js + React.js + Node.js

##### About MERN

- **MongoDB:** A NoSQL database that stores data in JSON-like documents.
- **Express.js:** A web application framework for Node.js.
- **React:** A JavaScript library for building user interfaces.
- **Node.js:** A JavaScript runtime for server-side programming.

##### Pros of using MongoDB here:

- MongoDB is highly scalable and flexible.

---

#### What does PERN stands for?

PERN: PostgreSQL + Express.js + React.js + Node.js

##### About PERN

- **PostgreSQL:** A powerful, open-source relational database.
- **Express.js:** Same as in MERN.
- **React:** Same as in MERN.
- **Node.js:** Same as in MERN.

##### Pros of using PostgreSQL here:

- PostgreSQL supports complex queries and transactions, making it suitable for applications requiring robust data integrity.
- Strong support for SQL, which is widely used and understood.

---

#### (M + P)ERN Stack

Combining MongoDB and PostgreSQL in a single stack can offer the best of both worlds:

1. Use MongoDB for handling unstructured data and high scalability.
2. Use PostgreSQL for structured data and complex queries.
3. Flexibility to choose the best database for different parts of your application.
4. Can leverage the strengths of both NoSQL and SQL databases.
5. Best for projects that can benefit from both NoSQL and SQL databases

---

#### An optional and suggested change that could be beneficial for your app

Replacing Node.js with Nest.js for your (M + P)ERN stack depending on your project’s needs and your team’s expertise

##### Node.js pros:

- Lightweight and efficient.
- Large ecosystem with a vast number of libraries and frameworks.
- Flexible and unopinionated, giving you more control over how you structure your application.

##### Nest.js pros:

- Strongly opinionated, providing a clear structure and best practices.
- Built-in support for TypeScript, enhancing code quality and maintainability.
- Modular architecture, making it easier to manage and scale large applications.
- Integrated support for features like dependency injection, which simplifies development.

###### Which One to Choose?

- **Node.js:** Choose this if you prefer flexibility and have experience with setting up and managing your own application architecture. It’s great for smaller projects or if you want to have more control over your codebase.
- **Nest.js:** Opt for this if you want a well-structured, scalable, and maintainable application with built-in best practices. It’s particularly beneficial for larger projects and teams, or if you appreciate the benefits of TypeScript.

---

### Different parts of our Stacks

#### React (TypeScript + SWC) + MUI

**React:** A popular JavaScript library for building user interfaces, particularly single-page applications. React continues to be a dominant force in web development, and its popularity is expected to grow even more in 2024 and 2025.

**TypeScript:** A superset of JavaScript that adds static typing, which helps catch errors early and improves code quality and maintainability.
[TypeScript Ultimate Course](https://youtu.be/d56mG7DezGs?si=Xl4RSkuPaRcaFiQR)
[Learn TypeScript](https://youtu.be/SpwzRDUQ1GI?si=t8bA3jHbV9oBiWKd)
[TypeScript Full Course for Beginners](https://youtu.be/gieEQFIfgYc?si=7bemq5IcwwzjYEW1)
[Learn TS](https://youtu.be/30LWjhZzg50?si=IrcWeYfWD-YRswjn)

**React with TypeScript:** Using TypeScript with React enhances the development experience by providing type safety, which helps prevent bugs and makes the code easier to understand and maintain. _Here are some links to dive deeper, also feel free so search for more:_
[React TypeScript Tutorial Playlist](https://react-typescript-cheatsheet.netlify.app/https://youtube.com/playlist?list=PLC3y8-rFHvwi1AXijGTKM0BKtHzVC-LSK&si=Omx5y4IqrZodOFpi)
[React.js & TypeScript](https://youtu.be/FJDVKeh7RJI?si=PL1D5c1dpv1xzSIw)

**SWC:** Integrating SWC with React and TypeScript speeds up the development process by providing faster compilation times. This is particularly beneficial in large projects where build times can become a bottleneck.

**MUI:** A React component library that implements Google’s Material Design guidelines. Using MUI with React allows you to quickly build a polished and professional-looking UI. MUI’s components are designed to be easily integrated into React applications, and they come with built-in support for theming and customization
[MUI Doc](https://mui.com/)
[React Material UI Tutorial](https://youtube.com/playlist?list=PLC3y8-rFHvwh-K9mDlrrcDywl7CeVL2rO&si=w3MYv3Wp3k3tZgRD)
[Material UI Tutorial](https://youtube.com/playlist?list=PL4cUxeGkcC9gjxLvV4VEkZ6H6H4yWuS58&si=2SwqTrjqfUpVn1nB)

#### Node.js

Node.js continues to be a cornerstone in backend development, and its relevance and demand are only increasing.

**_Links to learn Node.js:_**
[Node.js Website](https://nodejs.org/en)
[Node.js Tutorial for Beginners: Learn Node in 1 Hour](https://youtu.be/TlB_eWDSMt4?si=kmX7dUEqreRCLgJM)
[Node.js and Express.js - Full Course](https://youtu.be/Oe421EPjeBE?si=IZjtJOrEuIiE-_es)
[Node.js Full Course for Beginners | Complete All-in-One Tutorial | 7 Hours](https://youtu.be/f2EqECiTBL8?si=2iv5jJXCFYXmn9qk)
[Node.js Tutorial Playlist](https://youtube.com/playlist?list=PLC3y8-rFHvwh8shCMHFA5kWxD9PaPwxaY&si=tnw1dCgmC0NYljzE)

#### Nest.js

Nest.js is a progressive Node.js framework for building efficient, reliable, and scalable server-side applications. It leverages TypeScript by default (though it also supports JavaScript) and is heavily inspired by Angular’s architecture.

**_Links:_**
[Nest.js Full Course for Beginners | Complete All-in-One Tutorial | 3 Hours](https://youtu.be/8_X0nSrzrCw?si=rGMNMjUC-MVWjXMB)
[Learn NestJS – Complete Course](https://youtu.be/sFnAHC9lLaw?si=iTIfZnywJfUJaI9w)
[NestJs Course for Beginners - Create a REST API](https://youtu.be/GHTA143_b-s?si=cOJrC_PzJz1PGON8)
[Nest.JS Tutorials Playlist](https://youtube.com/playlist?list=PL_cUvD4qzbkw-phjGK2qq0nQiG6gw1cKK&si=cCNEqwcoRqukSpZ7)

#### Mongodb

MongoDB is a powerful and versatile NoSQL database that offers flexibility, scalability, and high performance. Its document-oriented model and rich feature set make it an excellent choice for modern applications that require dynamic schema design and efficient data handling.

**_Links:_**
[Complete MongoDB Tutorial Playlist](https://youtube.com/playlist?list=PL4cUxeGkcC9h77dJ-QJlwGlZlTd4ecZOA&si=1u1M4JKvKmCdjfdu)

**_PostgreSQL_**
PostgreSQL is a powerful and versatile RDBMS that offers advanced features, high performance, and strong security. Its extensibility and active community support make it an excellent choice for modern applications requiring robust data management.

**_Links:_**
[Learn PostgreSQL Tutorial - Full Course for Beginners](https://youtu.be/qw--VYLpxG4?si=1aiI043Kdi6XwFGQ)

#### Docker

Docker is an open-source platform that enables developers to automate the deployment, scaling, and management of applications using containerization. Containers package an application and its dependencies into a standardized unit, ensuring consistency across different environments. Docker revolutionizes the way applications are developed, deployed, and managed by providing a consistent, efficient, and scalable containerization platform. Its extensive ecosystem and integration capabilities make it a powerful tool for modern application development.

**_Links:_**
[Docker Tutorial for Beginners](https://youtu.be/pTFZFxd4hOI?si=XFZK90BRte6mXdKO)

#### Git

Git is a free and open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It is a powerful and versatile version control system that has become the standard for modern software development. Its distributed nature, performance, and robust feature set make it an essential tool for developers and teams working on projects of any size.

[Git and GitHub for Beginners - Crash Course](https://youtu.be/RGOj5yH7evk?si=2hbvCQK9DsM_H2rI)
[Git Tutorial for Beginners: Learn Git in 1 Hour](https://youtu.be/8JJ101D3knE?si=Ga3BvRm1JW09ioRy)

[_Doc Basic Git Instructions_](https://github.com/MuhammadKhalilzadeh/basic-git-instructions)
[_Git Collaborative Workflow Tutorial_](https://github.com/ajhollid/bluewave_collaborative_git)

---

### Concepts and Skills that we will use

#### Clean Architecture

Clean Architecture is a software design philosophy introduced by Robert C. Martin (also known as “Uncle Bob”). It emphasizes the separation of concerns, ensuring that the business logic of an application is decoupled from its external dependencies, such as databases, frameworks, and user interfaces.

Clean Architecture organizes code into distinct layers, each with a specific responsibility. This typically includes layers for entities, use cases, interface adapters, and frameworks.

Each layer is independent of the others, allowing for changes in one layer without affecting the others. This makes the system more maintainable and adaptable.

In our project, **VerifyWise**, we will focus on having following layers:

- **Presentation Layer:** This layer is responsible for handling the user interface and user interactions. It includes components like views, controllers, and presenters.
- **Application Layer:** This layer contains the business logic and application-specific rules. It orchestrates the flow of data between the presentation layer and the infrastructure layer.
- **Infrastructure Layer:** This layer handles the technical details and external dependencies, such as databases, web services, and file systems.

#### Benefits of Clean Architecture

- **Maintainability:** By separating concerns and adhering to SOLID principles, Clean Architecture makes the codebase easier to maintain and extend.
- **Testability:** The decoupled nature of the architecture allows for easier unit testing of individual components.
- **Flexibility:** Changes in technology, frameworks, or external systems can be made with minimal impact on the core business logic.
- **Scalability:** The modular structure supports the development of scalable applications.

#### Current Trends and Adoption

Clean Architecture has gained significant traction in recent years, especially among large enterprises and tech giants. Companies like Amazon, Google, and Microsoft have adopted Clean Architecture principles to build scalable and maintainable systems. The approach is particularly popular in industries where software longevity and adaptability are crucial, such as finance, healthcare, and e-commerce.

**_Links to learn more about Clean Architecture_**:

[The Clean Code Blog by Robert C. Martin (Uncle Bob)](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[Understand Clean Architecture in 7 Minutes](https://youtu.be/1OLSE6tX71Y?si=YpC536y0YTRcls80)
[React: How to Apply Clean Architecture](https://youtu.be/qOH2X5hciiA?si=KfMEvaXFHJyTS0ig)

#### Unit Testing, TDD, BDD and Integration Tests

**Unit Testing**
Unit testing involves testing individual components or units of a program in isolation from the rest of the application. These units are typically functions or methods.

**Test-Driven Development (TDD)**
TDD is a software development methodology where tests are written before the actual code. The process follows a cycle of writing a test, making it pass, and then refactoring the code.

**Behavior-Driven Development (BDD)**
BDD extends TDD by writing tests in a natural language that non-technical stakeholders can understand. It focuses on the behavior of the application from the user’s perspective.

**Integration Tests**
Integration testing involves testing multiple components or systems together to ensure they work correctly as a whole. It focuses on the interactions between units.

#### Documentation

**JSDoc**
JSDoc is a markup language used to annotate JavaScript code with comments that describe the structure and behavior of the code. These comments can then be processed by tools to generate comprehensive documentation in formats like HTML, making it easier for developers to understand and use the code1.

[Doc](https://jsdoc.app/)

---

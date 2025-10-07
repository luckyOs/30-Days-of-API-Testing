# 30-Days-of-API-Testing
30 Days of API Testing

💻 30 Days of API Testing Challenge: My Journey
A personal repository to document my progress through the Ministry of Testing's #30DaysOfTesting challenge, focused on API Testing. This challenge is a fantastic way to solidify fundamental concepts and explore new tools and techniques in the world of API Quality Assurance.

🎯 Project Goal
To complete all 30 daily tasks, documenting the concepts learned, tools used, code created, and key takeaways for each day, utilizing Java/RestAssured and Postman.

🛠️ Tools & Technologies Used
API Platform: Restful-Booker Platform
Automation Framework: Java, Maven
Testing Library: RestAssured
Manual/Exploratory Tool: Postman
Assertion Library: Hamcrest
Version Control: Git / GitHub

✅ Challenge Progress (Daily Log)

💻 Code Structure
This project is a Maven-based Java project.

.
├── src/
│   ├── main/
│   │   └── java/
│   └── test/
│       ├── java/
│       │   └── com/apitesting/
│       │       ├── POSTRequest.java  // Login & Token retrieval
│       │       ├── GetRoom.java      // GET requests and assertions
│       │       └── BookingTests.java // Full workflow scenarios
│       └── resources/
│           └── testdata/             // Data files for Day 30
└── pom.xml                           // Maven dependencies (RestAssured, JUnit, Hamcrest)


📝 Key Concepts Learned (Post-Challenge Review)
Authentication: Moving from Basic Auth to Token-based (Cookie) authentication for subsequent API calls.

Payload Management: Creating and serializing JSON payloads using simple Strings and external POJOs (Plain Old Java Objects).

Assertion Depth: Verifying not just the status code, but also response schema and data types using Hamcrest matchers.

Tool Comparison: When to use Postman (Exploratory) versus RestAssured (Automation).

🔗 Resources
Ministry of Testing: 30 Days of API Testing Checklist


The Restful Booker Platform

"Testing is an infinite loop of learning. Keep going!"

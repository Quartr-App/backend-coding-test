# Coding Challenge: Node.js Backend Developer (45 minutes)
In this challenge, you are required to create a RESTful API using Node.js that interacts with the JSONPlaceholder API (https://jsonplaceholder.typicode.com/).

Tasks:
1. Project Setup:
Initialize a new Node.js project. Set up Express.js and install necessary dependencies. Configure nodemon for automatic server restarts during development.

2. API Development:
Create a new endpoint GET /users/:id/posts in your application. This endpoint should accept a user id as a URL parameter, fetch the related user and their posts from the JSONPlaceholder API (https://jsonplaceholder.typicode.com/users/:id and https://jsonplaceholder.typicode.com/posts?userId=:id), and return them as a single JSON object.

3. Data Manipulation:
For each post fetched, add a new boolean field hasEvenId indicating whether the post's id is an even number. Use Array methods like .map() for this transformation.

4. Error Handling:
Implement error handling for your API. Ensure your application responds appropriately to potential issues like invalid user IDs, inability to connect to the JSONPlaceholder API, and other unexpected errors.

5. Testing:
Although we won't have time to write a complete test suite, briefly describe how you would go about testing this API endpoint, considering both successful scenarios and error cases.

6. Documentation:
Finally, document your new endpoint. Include details like the URL, method, parameters, successful response format, and possible error responses.

Please make sure to structure your code in a clean and modular way and to use async/await and promises where appropriate.

# Review (15 minutes)
After you complete the challenge, we will review your code together. During the review, we would like you to explain your solution, your choice of libraries, and any challenges you encountered. We are interested in your approach to problem-solving, your understanding of Node.js and JavaScript, and your ability to write clean, maintainable code. We will also discuss how you would test this endpoint and how you might handle potential improvements or extensions to your solution. Please be prepared to discuss and possibly demonstrate these elements.

Good luck!
Project built during Trybe course.
Participants: Marco Souza, Amanda Sottani, Carlos Rosa.

Q&A game application;

link: https://triviamarinafischer.netlify.app/

Frontend Library: React.js; Others: React Router, Redux; Middleware: Thunk; 

Endpoints:
- https://pt.gravatar.com/
- https://opentdb.com/api_config.php

On the login page, the email (someone@someone.com) is verified and it is also necessary to enter a name;
By clicking on the login button, the APIs are queried and the information is saved in localStorage and Redux, then the page is redirected to the game screen;
On the game screen there is a header with the person's information (gravatar, image and score);
The person has 30 seconds to answer each of the 5 questions;
It is only possible to respond to the game after 5s have elapsed;
At the end of the game, the person is redirected to the Feedback screen, where it is possible to see their score, how many questions they got right, come back to play again or see the ranking;
The ranking screen returns the information of the last games stored in localStorage;

**To get started, clone the repository and use the command npm install, then npm start;

# Dhivyaprakash N

I build web applications and investigate data questions. My current projects cover multiplayer room state, appointment booking, and a retrospective study of flight delays.

## Selected work

### The Paradox Room · Multiplayer systems

A browser mystery for 4–8 players. Each room has one server-side authority for phase changes, ballots, and private evidence. Each player receives a view limited to what they can see. The repository includes a four-client integration test that plays a round from lobby to reveal.

[Play a round](https://the-paradox-room.cookie-song-938.workers.dev/) · [Architecture and security](https://github.com/Dhivyaprakash-hub/the-paradox-room/blob/main/docs/architecture.md) · [Integration test](https://github.com/Dhivyaprakash-hub/the-paradox-room/blob/main/tests/multiplayer.integration.mjs)

### AeroPulse · Data and applied modeling

A retrospective comparison of two flight-delay models on the same cohort. The published results show a roughly six-second average absolute error improvement from adding prior-leg features. Candidate links are inferred from reported flights, and point-in-time aircraft assignment is unverified.

[Study and reproduction steps](https://github.com/Dhivyaprakash-hub/AeroPulse) · [Model card](https://github.com/Dhivyaprakash-hub/AeroPulse/blob/main/MODEL_CARD.md) · [Model implementation](https://github.com/Dhivyaprakash-hub/AeroPulse/blob/main/src/run_model_comparison.py)

### Careway · Java and React

A consultation-booking demo using fictional listings. A Spring transaction locks the doctor's row during booking, and a database constraint enforces uniqueness for each doctor, date, and time.

[Run locally](https://github.com/Dhivyaprakash-hub/Hospital-application#run-locally) · [Booking service](https://github.com/Dhivyaprakash-hub/Hospital-application/blob/main/backend/src/main/java/com/dhivya/consultation/AppointmentService.java) · [Database migration](https://github.com/Dhivyaprakash-hub/Hospital-application/blob/main/backend/src/main/resources/db/migration/V1__create_doctors_and_appointments.sql)

## More work

- [Wellnest](https://github.com/Dhivyaprakash-hub/demo-screen) · A React catalog with search, filters, saved items, and product comparison. [Open the demo](https://demo-screen-ivory.vercel.app/)
- [Taskflow](https://github.com/Dhivyaprakash-hub/Angular-POC) · An Angular task board with browser-local workspaces.
- [MindMate](https://github.com/Dhivyaprakash-hub/MindMate) · A browser journal with local storage, export, and deletion controls.
- [Climate Atlas](https://github.com/Dhivyaprakash-hub/Climatic_Visualization) · A coursework data explorer with country and month comparisons.
- [FRAME](https://github.com/Dhivyaprakash-hub/workshop-graphql-netflix) · A React film explorer rebuilt from a GraphQL workshop repository.

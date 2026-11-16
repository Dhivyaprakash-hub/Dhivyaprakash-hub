# Dhivyaprakash N

I build web applications and investigate data questions. My current projects cover multiplayer room state, appointment booking, and a retrospective study of flight delays.

## Selected work

### The Paradox Room · Multiplayer systems

A browser mystery for 4–8 players. A Cloudflare Durable Object owns each room's phase changes, ballots, and private evidence. The server sends each player a filtered view. A four-client integration test exercises a full round and verifies that a consumed WebSocket ticket cannot be reused.

[Play a round](https://the-paradox-room.cookie-song-938.workers.dev/) · [Architecture and security](https://github.com/Dhivyaprakash-hub/the-paradox-room/blob/main/docs/architecture.md) · [Integration test](https://github.com/Dhivyaprakash-hub/the-paradox-room/blob/main/tests/multiplayer.integration.mjs)

### AeroPulse · Data and applied modeling

A retrospective comparison of two flight-delay models on the same 2.82 million held-out flights. Prior-leg features reduced mean absolute error from 19.317 to 19.218 minutes, a gain of about six seconds per flight. Candidate links use reported flight records, and aircraft assignments at prediction time are unverified.

[Study and reproduction steps](https://github.com/Dhivyaprakash-hub/AeroPulse) · [Model card](https://github.com/Dhivyaprakash-hub/AeroPulse/blob/main/MODEL_CARD.md) · [Model implementation](https://github.com/Dhivyaprakash-hub/AeroPulse/blob/main/src/run_model_comparison.py)

### Careway · Java and React

A consultation-booking demo using fictional listings. A Spring transaction locks the doctor's row during booking, and a database constraint enforces uniqueness for each doctor, date, and time. The H2 integration test runs two concurrent booking calls for the same slot and checks that exactly one booking succeeds.

[Run locally](https://github.com/Dhivyaprakash-hub/Hospital-application#run-locally) · [Booking service](https://github.com/Dhivyaprakash-hub/Hospital-application/blob/main/backend/src/main/java/com/dhivya/consultation/AppointmentService.java) · [Concurrency test](https://github.com/Dhivyaprakash-hub/Hospital-application/blob/main/backend/src/test/java/com/dhivya/consultation/AppointmentConcurrencyTest.java)

## More work

- [Wellnest](https://github.com/Dhivyaprakash-hub/demo-screen) · A React catalog with search, filters, saved items, and product comparison. [Open the demo](https://demo-screen-ivory.vercel.app/)
- [Taskflow](https://github.com/Dhivyaprakash-hub/Angular-POC) · An Angular task board with browser-local workspaces.
- [MindMate](https://github.com/Dhivyaprakash-hub/MindMate) · A browser journal with local storage, export, and deletion controls.
- [Climate Atlas](https://github.com/Dhivyaprakash-hub/Climatic_Visualization) · A coursework data explorer with country and month comparisons.
- [FRAME](https://github.com/Dhivyaprakash-hub/workshop-graphql-netflix) · A React film explorer rebuilt from a GraphQL workshop repository.

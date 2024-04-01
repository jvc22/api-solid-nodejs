<h1><img align="center" height="30" src="/public/node-js.png"> Node.JS API SOLID</h1>

This back-end application is based on GymPass functional structure.

## Functional requirements

- [ ] It should be able for a user to register;
- [ ] It should be able to authenticate the data provided by the user;
- [ ] It should be able to obtain the profile of a logged in user;
- [ ] It should be able to obtain the number of done check-in's of a logged in user;
- [ ] It should be able for a user to get their check-in's history;
- [ ] It should be able for a user to search for near gyms;
- [ ] It should be able for a user to search for gyms based on their names;
- [ ] It should be able for a user to check-in in a registered gym;
- [ ] It should be able to register a gym.

## Business rules

- [ ] User should not be able to register using a duplicated e-mail;
- [ ] User should not be able to check-in twice in the same day;
- [ ] User should not be able to check-in if their distance to the gym is higher than 100m;
- [ ] Check-in should be able to be validated only until 20min after bbeing created;
- [ ] Check-in should only be validated by admins;
- [ ] Gym should only be registered by admins.

## Non-functional requirements

- [ ] User password should be encrypted;
- [ ] Application data should be persisted in a PostgreSQL database;
- [ ] Every data list should be paginated with 20 items per page;
- [ ] User should be identified by a JWT (JSON Web Token).
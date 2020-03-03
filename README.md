# Tagger - Smarter Email

You can find the project at [Tagger](https://tagger-lab.netlify.com/).

[![Maintainability](https://api.codeclimate.com/v1/badges/f0e8023998589cc4d94f/maintainability)](https://codeclimate.com/github/Lambda-School-Labs/tagger-fe/maintainability)

# Contributors

<h2>Team Lead</h2>
<center>

|                                              [Vlad Mogilevskiy](https://github.com/vladmog)                                               |
| :---------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Vlad.jpg" width = "200" />](https://github.com/vladmog) |
|                           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/vladmog)                            |

|[<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/vladmog/)

</center>

<br>
<h2>Web Team</h2>

|                                                 [Luis Flores](https://github.com/lflores0214)                                                 |                                                 [Mimi Hoang](https://github.com/meowmimi1)                                                  |                                               [Nathaniel Mosco](https://github.com/natemosco)                                               | [Raymond Trinh](https://github.com/RaymondTrinh91)                                                                                                  | [Andrew Wilson](https://github.com/easyas123l1)                                                                                                 |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Luis.jpg" width = "200" />](https://github.com/lflores0214) | [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Mimi.png" width = "200" />](https://github.com/meowmimi1) | [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Nate.png" width = "200" />](https://github.com/natemosco) | [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Raymond.jpg" width = "200" />](https://github.com/RaymondTrinh91) | [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Andrew.jpg" width = "200" />](https://github.com/easyas123l1) |
|                           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/lflores0214)                            |                           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/meowmimi1)                            |                           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/natemosco)                            | [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/RaymondTrinh91)                                                         | [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/easyas123l1)                                                        |
|     [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/luis-flores-523141194/)     |    [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/mimi-hoang-b09912189/)     |     [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/nate-mosco-98888ab4/)     |                                                                                                                                                     | [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/raymond-trinh-39115412a/)         | [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/andrew-wilson-055b55174/) |

<br>
<h2>DS Team</h2>

|                                                 [Rosie LaSota](https://github.com/apathyhill)                                                 |                                                 [Jean Fraga](https://github.com/JeanFraga)                                                  |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Rosie.jpg" width = "200" />](https://github.com/apathyhill) | [<img src="https://github.com/Lambda-School-Labs/tagger-fe/blob/master/src/images/Jean.jpg" width = "200" />](https://github.com/JeanFraga) |
|                            [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/apathyhill)                            |                           [<img src="https://github.com/favicon.ico" width="15"> ](https://github.com/JeanFraga)                            |
|          [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/apathyhill/)           |          [<img src="https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca" width="15"> ](https://www.linkedin.com/in/jeanfraga/)          |

</center>
## Project Overview

Introducing, [Tagger](https://tagger-lab.netlify.com/)!

[Trello Board](https://trello.com/b/fxTQlX74/labs-20-tagger-smarter-email)

[Product Canvas](https://www.notion.so/Tagger-Smarter-Email-01673a2ed9e54cb8834b959ad39f7de2)

#### Backend delpoyed at [Heroku](https://taggerhq.herokuapp.com/) <br>

## Getting started

To get the server running locally:

- Clone this repo
- **npm install** to install all required dependencies
- **node .** to start the local server
- **npm test** to start server using testing environment

### NodeJS

- NodeJS is a lightweight framework.
- The asynchronous nature of NodeJS makes it efficient for building API's.
- NodeJS is easy to learn if you know JavaScript.
- Since NodeJS is written in JavaScript, you can use one language for FE and BE.
- NodeJS scales well. Therefore, future additions may be added to this project by our group or another group at Lambda School.

## Endpoints for Frontend

#### Routes

| Method | Endpoint   | Access Control | Description            |
| ------ | ---------- | -------------- | ---------------------- |
| POST   | `/emails`  | Frontend Team  | receive all emails     |
| POST   | `/compose` | Frontend Team  | create and send emails |

# Data Model

#### Frontend

---

Post /emails

```
{
  email: STRING  ex: taggerlabs20@gmail.com
  host: STRING  ex: imap.gmail.com
  token: STRING ex: Use docs to create XoAuth2 token
}
```

Post /compose

```
{
  service: STRING ex: gmail
  host: STRING ex: smtp.gmail.com
  port: STRING ex: 465
  userEmail: STRING ex: taggerlabs20@gmail.com note: this is the user that is sending the email.
  receiver: STRING ex: somefakeemail@gmail.com note: this is the user that is receiving the email.
  subject: STRING ex: This is the subject for this email
  text: STRING ex: This is the body for this email
}

## Environment Variables

In order for the app to function correctly, the user must set up their own environment variables.

create a .env file that includes the following:

- credenials.json - this is downloaded from [here](https://console.developers.google.com/) for your specific API.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

Please note we have a [code of conduct](./code_of_conduct.md). Please follow it in all your interactions with the project.

### Issue/Bug Request

**If you are having an issue with the existing project code, please submit a bug report under the following guidelines:**

- Check first to see if your issue has already been reported.
- Check to see if the issue has recently been fixed by attempting to reproduce the issue using the latest master branch in the repository.
- Create a live example of the problem.
- Submit a detailed bug report including your environment & browser, steps to reproduce the issue, actual and expected outcomes, where you believe the issue is originating from, and any potential solutions you have considered.

### Feature Requests

We would love to hear from you about new features which would improve this app and further the aims of our project. Please provide as much detail and information as possible to show us why you think your new feature should be implemented.

### Pull Requests

If you have developed a patch, bug fix, or new feature that would improve this app, please submit a pull request. It is best to communicate your ideas with the developers first before investing a great deal of time into a pull request to ensure that it will mesh smoothly with the project.

Remember that this project is licensed under the MIT license, and by submitting a pull request, you agree that your work will be, too.

#### Pull Request Guidelines

- Ensure any install or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new plist variables, exposed ports, useful file locations and container parameters.
- Ensure that your code conforms to our existing code conventions and test coverage.
- Include the relevant issue number, if applicable.
- You may merge the Pull Request in once you have the sign-off of two other developers, or if you do not have permission to do that, you may request the second reviewer to merge it for you.

### Attribution

These contribution guidelines have been adapted from [this good-Contributing.md-template](https://gist.github.com/PurpleBooth/b24679402957c63ec426).

## Documentation

See [Frontend Documentation](https://github.com/Lambda-School-Labs/tagger-fe/blob/master/README.md) for details on the fronend of our project. <br>
See [Data Science Documentation](https://github.com/Lambda-School-Labs/tagger-ds/blob/master/README.md) for details on the data science of our project.
```

# Wave Prediction Skill

This is the implementation for Alexa Skill on wave forecast using Sufline v2 API.

## Setup

### Creating the skill

The skill was created using ASK CLI commands. A tutorial on how to do that can be found [here](https://developer.amazon.com/en-US/docs/alexa/smapi/ask-cli-intro.html).

    ask new

> Using "Intention model", "AWS Lambda" as host and "Hello World" template

    ask deploy

### Troubleshooting

1. *"The current revisionId (The revision ID for Lambda ARN (arn:XXX) should be YYY, but found ZZZ. Please solve this revision mismatch and re-deploy again."*

Update the "revisionId" on .ask/ask-states.json file on the root folder.
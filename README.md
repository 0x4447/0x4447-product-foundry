# 🌋 Foundry

This stack will create a Pipeline which will deploy any GitHub repository based on the actions specified in the `buildspec.yml` file.

# DISCLAIMER!

This stack is available to anyone at no cost, but on an as-is basis. 0x4447 LLC is not responsible for damages or costs of any kind that may occur when you use the stack. You take full responsibility when you use it.

# How to deploy

<a target="_blank" href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?templateURL=https://s3.amazonaws.com/0x4447-drive-cloudformation/foundry.json">
<img align="left" style="float: left; margin: 0 10px 0 0;" src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>

All you need to do to deploy this stack is click the button to the left and follow the instructions that CloudFormation provides in your AWS Dashboard. Alternatively you can download the CF file from [here](https://s3.amazonaws.com/0x4447-drive-cloudformation/foundry.json).

# What will deploy?

![Foundry Diagram](https://raw.githubusercontent.com/0x4447/0x4447-product-foundry/assets/diagram.png)

The stack takes advantage of AWS S3, AWS SES, AWS Lambda, and the AWS Trigger system to tie everything together. You'll get:

- 1x CodePipelines
- 1x CodeBuilds

# How to work with this project

When you want to deploy the stack, the only file you should be interested in is the `CloudFormation.json` file. If you'd like to modify the stack, we recommend that you use the [Grapes framework](https://github.com/0x4447/0x4447-cli-node-grapes), which was designed to make it easier to work with the CloudFormation file. If you'd like to keep your sanity, never edit the main CF file 🤪.

# The End

If you enjoyed this project, please consider giving it a 🌟. And check out our [0x4447 GitHub account](https://github.com/0x4447), where you'll find additional resources you might find useful or interesting.

## Sponsor 🎊

This project is brought to you by 0x4447 LLC, a software company specializing in building custom solutions on top of AWS. Follow this link to learn more: https://0x4447.com. Alternatively, send an email to [hello@0x4447.email](mailto:hello@0x4447.email?Subject=Hello%20From%20Repo&Body=Hi%2C%0A%0AMy%20name%20is%20NAME%2C%20and%20I%27d%20like%20to%20get%20in%20touch%20with%20someone%20at%200x4447.%0A%0AI%27d%20like%20to%20discuss%20the%20following%20topics%3A%0A%0A-%20LIST_OF_TOPICS_TO_DISCUSS%0A%0ASome%20useful%20information%3A%0A%0A-%20My%20full%20name%20is%3A%20FIRST_NAME%20LAST_NAME%0A-%20My%20time%20zone%20is%3A%20TIME_ZONE%0A-%20My%20working%20hours%20are%20from%3A%20TIME%20till%20TIME%0A-%20My%20company%20name%20is%3A%20COMPANY%20NAME%0A-%20My%20company%20website%20is%3A%20https%3A%2F%2F%0A%0ABest%20regards.).
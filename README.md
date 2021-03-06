**[Setup](#setup)** | **[Presentation](#presentation)** | **[Contact](#contact)** | **[Useful Links](#useful-links)**

# AWS Serverless Workshop

Example code for the 2018 AWS Community Day Midwest workshop seminar on Serverless, presented by Tyler Hendrickson.

## Setup

We will be leveraging Python and the Serverless framework for this workshop. For a full list of instructions for Mac and Windows please reference our [Install Guide](documentation/InstallGuide.md)


## Presentation

Slides for the presentation are available [here](https://github.com/shiftgig/aws-serverless-workshop/blob/master/presentation-slides.pdf) 
in the master branch of this repository.

Note that the [`master`](https://github.com/shiftgig/aws-serverless-workshop/tree/master) branch of this repository
corresponds to the content in the presentation up to "Step 5" (end of slide 38).

If you'd like to see the fully-complete example, take a look at the [`final`](https://github.com/shiftgig/aws-serverless-workshop/tree/final)
branch. Additional functionality found on this branch includes:
* DynamoDB integration
* Support for GET and DELETE requests (in addition to PUT)
* Advanced API Gateway usage: protecting endpoints with a client API key and usage plan


## Contact

You can get in touch with me via email: [hendrickson.tsh@gmail.com](mailto:hendrickson.tsh@gmail.com)


## Useful Links

* Serverless Framework
    * [Github repository](https://github.com/serverless/serverless)
    * [Website](https://serverless.com/)
* `serverless-python-requirements` plugin
    * [Github repository](https://github.com/UnitedIncome/serverless-python-requirements)
* Pipenv: Python Dev Workflow for Humans
    * [Website](https://docs.pipenv.org/)
    * [Github repository](https://github.com/pypa/pipenv)

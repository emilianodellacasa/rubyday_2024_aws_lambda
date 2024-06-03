# Using Ruby on AWS Lambda

Sample code for my talk at RubyDay 2024 "Using Ruby on AWS Lambda"

## How to start

First of all, AWS command line must be installed and configured with the right credentials, depending on your architecture

```bash
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
```

Then, you need to install the serverless framework and th eplugin for ruby gems

```bash
npm install -g serverless
npm install --save serverless-ruby-layer
```

Then, run the following command to create a new project

```bash
sls
```

Then, you can deploy the project with the following command

```bash
sls deploy
```





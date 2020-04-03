This project serves a quick start for using authentication with Amplify and a React front-end.

## Get started

### Pre-requisites

1. Install AWS Amplify cli

```bash
npm install -g @aws-amplify/cli
```

2. Configure cli

```bash
amplify configure
```

### Init Amplify and add auth

To initialize an Amplify project, run

```bash
amplify init
```

and choose all defauls and an AWS profile.

Then, add authentication by running

```bash
amplify add auth
```

and choosing all defaults, except for "How do you want users to be able to sign in?", where you select Email.

### Update backend and run app

To update the AWS backend, run

```bash
amplify push
```

and then launch a local webserver and install all dependencies by running.

```bash
npm install && npm start
```

### Delete

To delete all back-end infrastructure,
run

```bash
amplify delete
```

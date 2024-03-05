# wing-cdk

Using Wing to author AWS apps and deploy to CloudFormation via CDK.

## Prerequisites

- [Install Wing](https://www.winglang.io/docs/)
- [Install AWS CDK Toolkit](https://docs.aws.amazon.com/cdk/v2/guide/cli.html)

## Install dependencies

```sh
npm install
```

## Run locally

Start the [Wing Console](https://www.winglang.io/docs/start-here/local):

```sh
npm start
```

![Wing Console](https://github.com/lukehedger/wing-cdk/assets/1913316/59400ba7-72fe-4ab5-805e-c10b6c1e2467)

## Test Wing app

```sh
npm test
```

## Build Wing app

```sh
npm run build
```

\* Compiles the Wing app to an AWS CloudFormation stack

## Deploy Wing app

```sh
npm run deploy
```

\* Uses the AWS CDK Toolkit to deploy the Wing app to AWS

## Resources

- [Wing -> CDK](https://www.winglang.io/docs/tools/cli#awscdk-platform)
- [More examples](https://github.com/winglang/examples/tree/main/examples/provider-specific/awscdk-hello-wing)
- [Wing](https://www.winglang.io/)
- [AWS CDK](https://aws.amazon.com/cdk/)

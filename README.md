# Serverless Typescript Bootstrap

## Overview

This is a basic starter kit for Serverless w/ Typescript & Serverless Offline pre-installed.

## Getting Started

```sh
# Install n to easily swap between NodeJS versions
npm i -g n
# Currently, the latest NodeJS runtime version supported by AWS is v12.x.y.
# You'll want to grab the last official release (12.19.0).
n 12.19.0
# Make sure you have the correct version installed (should show v12.19.0)
node -v
# Install Serverless globally
npm i -g serverless
# Install the dependencies in this repository
yarn install
# Start serverless locally
yarn start
# You should now be able to hit: http://localhost:3000/dev/health
```

## Resources

| Name                                                                                            | Description                  |
| :---------------------------------------------------------------------------------------------- | :--------------------------- |
| [Serverless][serverless]                                                                        | Serverless Framework         |
| [Serverless Typsecript Plugin](https://www.serverless.com/plugins/serverless-plugin-typescript) | Serverless Typescript Plugin |
| [Serverless Offline](https://github.com/dherault/serverless-offline)                            | Serverless Offline (Local)   |

[serverless]: https://github.com/serverless/serverless

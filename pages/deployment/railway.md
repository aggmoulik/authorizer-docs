# Deploy on [railway.app](https://github.com/authorizerdev/authorizer-railway)

## Create Instance

Deploy production ready Authorizer instance using [railway.app](https://github.com/authorizerdev/authorizer-railway) with postgres and redis for free
<br/>

<a target="_blank" href="https://railway.app/new/template/nwXp1C?referralCode=FEF4uT"><img src="https://railway.app/button.svg" alt="Deploy on Railway"/></a>

After clicking the above button, follow the steps mentioned below:

### Step 1: Give permission for Github

Railway app will create a repository in your github account and will use that for further deployments

<img src="/images/railway.png" />

### Step 2: Set the repository name

Default repository name will be `authorizer-railway` but you can choose a different name and domain will be created accordingly

### Step 3: Setup Instance

- Open authorizer instance endpoint in browser
- Sign up as an admin with a secure password
- Configure environment variables from authorizer dashboard. Check env [docs](/core/env) for more information

> Note: `DATABASE_URL`, `DATABASE_TYPE` and `DATABASE_NAME` are only configurable via platform envs

## Update Instance

Update existing Authorizer on existing instance

- You can update the [docker image](https://github.com/authorizerdev/authorizer-railway/blob/main/Dockerfile#L1) to the desired version in your repository which gets created with your deployment.

- You can find all the versions on [github](https://github.com/authorizerdev/authorizer/releases) or [dockerhub](https://hub.docker.com/r/lakhansamani/authorizer)

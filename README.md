# Recommender Systems in the Cloud Workshop - November 2024

Welcome all to this workshop. We will build a recommendation engine and deploy it on two of the most used cloud tools in this space: Snowflake and SageMaker.

## Pre-requisites

Before coming to the workshop, you **MUST** complete all the steps that follow. If you don't, you will not be able to play around with the technology when you are on site!

### What We Need

- A Linux machine
- Docker
- An AWS free trial account with adequate resources for machine learning
- A Snowflake free trial account
- A Serverless account (free)

#### Linux Machine

Coming with a Linux machine is not mandatory, but you will have a hard time following and we cannot help debug Windows machines (or Mac).

#### Docker

Install Docker by following the steps in the [Docker installation guide](https://docs.docker.com/get-docker/).

#### AWS Account

1. Create a fresh AWS account. You can use your Gmail email address or any other account that supports the "+" trick. This trick allows you to create multiple accounts with the same email on one website.
2. Once your account is created, you will have to request the resources that we will use during the workshop. These resources are part of the free plan, but you will have to have them approved by AWS support anyway. Approval will take around 2-5 days, so make sure to request early enough to not come unprepared!

#### To Request:

1. Go to the **Service Quotas** section of your AWS account.
2. On the top right corner, where it says **Manage quotas**, type in "sage" and select **Amazon SageMaker**, then click **View quotas**.
3. In the **Search by quota name** box, type in `ml.m4.xlarge`.
4. Here you will have to request two quota increases, one for **ml.m4.xlarge for training job usage** and one for **ml.m4.xlarge for endpoint usage**.
5. For each one, select the minimum number of resources allowed and submit the request.

AWS will review your case and allow you access to the compute after a few days.

#### Snowflake

We will use Snowflake as a data warehouse. You will discover what this is during the workshop.

For now, create an account with any institutional email address. In my case, I used my company account that has a `qima.com` domain. You can use your school email address or any other, outside Gmail, Outlook etc. This will grant you a 30-day free trial access.

#### Serverless

1. Go to [serverless.com](https://www.serverless.com) and register an account.
2. Follow their instructions to install the Serverless framework on your machine and check if it's working.

For non-commercial uses, this service is free, so don't worry about free tiers.

---

If you have any question or concern, message me on Facebook at [Vittorio Rossi](https://web.facebook.com/profile.php?id=100010409105751). I will be happy to get you ready for our intense, hands-on workshop in the cloud!

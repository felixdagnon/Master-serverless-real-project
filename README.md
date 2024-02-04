# Master-serverless-real-project
Master Serverless real project

# LevelUp! Lab for Serverless

## Lab Overview

## Setup

### Creating API with Lambda integration

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/e2ab0230-f6f2-4121-a49b-1834a159fddd)

### Creating simple Lambda function as back end

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a095c234-14aa-4563-85fa-18faaf0c2aa7)

### Creating GET API

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/d09d392b-a836-4df4-981c-32f0987ebfca)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6ece177c-d472-48a9-9f39-2e0f1bb9b138)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/5d61c57b-9428-45dd-9518-445a7de1031c)

Click the url to download letter

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/fcdbedfa-97fc-42e5-a6d3-ad8e3bab455d)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/e5c7766c-1e47-44bf-874e-ab56a4fac9ef)

### Test the GET API in API gateway console

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/657e53e9-e6cd-4c37-b415-5ad7e1a16499)

### Deploy the API into a stage

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6d492652-7c90-4be5-9d67-f2201070dbbd)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/b9029269-bfc6-44eb-a301-aa2d719237bd)

### Invoking the GET APi from internet

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a80f9536-b38d-402a-a16b-2d65b8fec189)

### Create POST APi with new lamba function

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a291c6c7-8afd-4819-b79e-aed8d3427ab8)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6aafb0f3-40a0-468d-8bbc-afc36c744564)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/3efa66e3-38c4-4025-a175-6b980921c294)

### Test the POST API in API gateway console

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/bb035400-85c4-4239-ac58-b7e4e9725b53)

### Invoking the POST APi from POSTMAN

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/789fc2af-7501-4f2a-955b-c278b4d92541)

### APi Gateway query parameters

Vhere we can send input parameter in the get methode for example region

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/7ba55def-dfde-46ec-9fa0-7d229261addf)

Create new API  GreatfromCountry (example) and new methode GET

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f9602c75-0584-42d8-96e1-e3860540950b)

Create query parameters

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/dddb26de-b3a2-4754-8720-82460f5397df)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/00ef8e8f-0305-4844-b1cf-72cf60aeb9b8)

### Test the query parameters GET API in API gateway console

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/2a83bfc9-7de0-4528-b067-e354dd89a6a6)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a4ee3d18-028a-4dc7-9ac2-be78718107fe)

### Invoking the GET APi query parameters from POSTMAN

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/19c458f7-a7a5-47c6-b1b2-ed4fd3932c77)

For example add '?nameofcountry=England' at the end of url and test ok

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/2d0fec75-cfd5-4cb4-bbcf-0a7402f7d70c)


### Demo AWs cross account in the API Gateway

Lambda from second account

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/be49d2c1-6e4d-4f97-9051-07cd5104b67a)

API Gateway in the first account

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/e9f581ae-ea70-4455-883e-7db5dee75544)

API Gateway should call lambda from second account and return 'hello word'

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/8e6ad15a-52ca-4206-a032-c340d6f656ec)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/95c0626e-52c4-4ffc-98e4-71f6973ecf82)

From the second acount copy the full arn of lambda

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/b5bd3e2e-c6a2-4817-893b-d6708f237263)

And paste it in the path of lambda function in the first account

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/ceacce45-1957-4ba0-8345-4207034a2308)

And check mark

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/8239a361-e065-4bfa-a31f-3853a7ec1720)

Copy those permissions  and attech to lambda in the second account by using Cloud9 IDE with AWS CLI

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/e56f1cf9-b256-465e-8adf-0fe1cb2cb004)

Test ok from first account (API Gateway account)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/5f49e9cd-df8b-4a75-98ca-e3f0f07c16f1)


### Lambda Version and Alias for API Traffic Splitting for Blue Green deployment

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9021ec42-b7e2-42db-b96d-ebf2e240f340)


Create a new lambda function versionTest

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f7629b28-bd22-458f-a048-7396b21d7568)

Publish a new version

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/24a1807c-ec52-4345-baa8-a813d1851a6c)

versionTest pointing to version 1 (new version)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/0f8c1097-724b-4b2b-a27e-fffa1e8b8c1e)

Create Test event

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/4094bd6a-3f98-4ac5-8174-90c625588539)

Testing version 1 

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/c075be27-d6ac-46a0-b8cf-bc0df2b4d8e4)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/018c811a-363c-4461-898d-7cf32554b4a2)

Publish New Version (version 2)  from versionTest

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/85400c29-2de7-421a-a9eb-ac03bab05c12)

Publish New Version (version 3)  from versionTest

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/33f624ea-ec15-497e-9bde-a5ef2ddcb9e3)

Publish New Version (version 4)  from versionTest

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9064fb71-2a0b-48e1-8bbb-061fe2e65347)

Create Alias and trafic shifting

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/84772a7d-1052-40c2-96bb-c9b9e1b20e81)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/4893b4dd-d374-4cc9-848e-6656ce7bd3fa)

Testing Alias trafic shifting version 1 and version 4

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/40d6796d-e566-43fd-8050-c020e317ac35)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9e0fb25d-61a0-457c-b80a-ad41cca536a1)

###  API Traffic Splitting using Lambda Version and Alias for for Blue Green deployment

Create API aliasTest resource and GET methode

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a2b64d01-b17c-4464-b3c5-23e162823abf)

Replace in the GET methode lambda function with versionTest:${stageVariables.lambdaAlias} in integration request

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/5008dd2c-dc79-4217-ac2f-0ef3525430b7)

In the permission: replace ${stageVariables.lambdaAlias} with the name of Alias (oldestNewest) in notepad

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f6741b9a-8019-44a1-a11e-8c9957713dda)

After change, paste the permission in Cloud9 IDE and enter

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/5c8dd272-74c4-45d0-b34f-e33cbad01810)

Deploy API in Dev

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/da41e3ce-2d05-48ff-a8c6-376ccda78f82)

Add stage variables and save

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/296e9c7b-1fc5-490e-be6f-c9ee554f07da)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/cd516a74-0eb2-49a8-8182-f1b3deabdf83)

For Prod, we can deploy API in Prod, create stage variables and point lambdaAlias to prodAlias (we can send the trafic to different version of lambda)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/eadebc1f-1832-40e3-bdb6-5d5d4eadc4f1)

Testing API same behaviour as lambdaAlias

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/1a7f11de-8e24-4f86-b47e-1d9890f153ed)

Copy url and paste in the browser

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/153fbb18-1bf9-4faa-b0e9-781c53cf58d6)h

Refresh

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/c5769553-6527-48ea-90ad-4315daed1c36)

### Canary deplyment of API

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/7e9c0106-69c6-4ddb-a8ce-feb30e36d137)

If ok

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/90e72a58-34f5-4f9c-8690-d612cd6eb42d)

Demo: create two lambda functions call canaryLambdaBase and canaryLambdaModified

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/5ab056b5-d763-4b43-ac6b-e15cb41ff267)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/191d3ccd-ff2a-40bb-9b3a-21a04fd5dd9c)

Create canary API calls canaryTest using canaryLambdaBase function and GET methode

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6ffb2b0f-19d4-42cc-aebf-f4208e7c2d08)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/03bb61c2-550e-4671-a50f-9e75b618e6a8)

Using canary tb to point to the new lambda function (canaryLambdaModified) and create canary

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/17c021f3-e740-4b7f-b31c-43fd3fe39957)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/fb5500f2-34c7-4fd7-98ef-c3b289157d09)

In Ressource change canaryLmbdabase to canaryLambdaModified

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9575c936-2faf-4fc9-8cd1-f52f8f7ddb9a)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/2fc81d1e-4197-43e2-9fa2-c4dd4e9a1389)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/1313fca5-5514-4b3c-85f1-eab360587577)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/d0f71b9b-efdb-4f9c-a04d-918977d8c6be)

Eddit canary setting

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f70dc795-aac4-4daf-806b-280bf8768f66)

Trafic 50% go to base and 50% to modified when we refresh url

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/00f6b12b-3215-4254-8a81-dae39c5cbead)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/43418196-465b-4cd7-989f-3e35b87a7cd8)

If canary test ok, we PROMOTE the canary

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/3d8fa953-ce89-458d-8833-4393e3dcdf51)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6dbefa19-f239-4bb5-84b9-75e41660035d)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/de448c94-c67c-4538-85b9-1cea6fb75d3f)


###  API Endpoint

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/4d86c1b4-5112-429e-9818-1e506802dfa4)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f8729357-485b-4997-99d8-8d275d45792b)

###  API caching

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/ed06d5ed-fedd-45f2-8c93-8719c4779c9e)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/252ea745-a115-4cb1-b82f-a925bfd412c1)

Ennable cache setting and modified parameters (capacity and TTL for the cache...)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/4ab9d2c9-09fb-4961-a960-90248269f077)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/8da4abc8-390e-4a88-8090-c01f8bc18c5d)

### Demo API SWAGGER

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9fa60200-a880-43f1-b8ba-4d2570f941db)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/95fe699b-a5bd-43de-81be-ff41db6143a3)

Export API GAEWAY API as Swagger

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/2205ee0d-3ff3-4f8c-93e0-c355923ea3da)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/3b220055-2229-40fd-b395-dc28de3c35bd)

Create API with Swagger

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/c1aaf6ed-a9ad-47cd-8362-eae682939ae7)


### CORS(Cross Origin Resource Sharing)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/fc3569d7-7fb2-4b33-9c22-5770d0f3e5c9)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/3f5f5f12-7648-4b3a-8927-080d4773cbf7)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/3d031fcc-452a-4684-8c76-863cb0462713)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/b64a983e-00b6-4f91-84d1-557d0e22371e)

### Create new lambda function using external dependencies requests 

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/7f05da2d-36ed-40bf-a63a-34e7b7742a7a)

### Use visual studio code to invoke

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/820aea92-c062-4b8b-976b-633f6f47ab99)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/7eac9583-f486-44b4-a462-60d5e63a91bd)

![image](https://github.com/felixdagnon/Serverless-project/assets/91665833/c4a5f1c5-a244-4133-b57f-2494bc1c0d25)

Resquests are upload

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/74a933f2-387c-4476-919f-ad6fd84701dd)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/03cbb76d-1d5e-4c45-b595-c1b584a9fe72)

###Solving external dependencies requests using Cloud9

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/7f8209b0-4a88-42a0-8465-ce8668a5f42f)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f47b5cef-a0c9-46c6-a2f4-3a2aa463cf02)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/757a06f5-32a1-43ed-b80d-7d7c4a4f16f4)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a443e7a1-1da6-4846-89dd-c1a5a79543dd)

### REINVENT 2020 lambda container image

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/88b102ba-32e5-4607-8d1a-7411c72d6566)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/72ccd1ca-b87f-461c-a3b0-9df3773641bb)

in Cloud9 create lambda node container

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f76d2f77-896d-457e-9a25-2b097ee99c87)

Using this blog post to create app.js

https://aws.amazon.com/blogs/aws/new-for-aws-lambda-container-image-support/

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a13bbcde-d90b-4084-b95a-9604995bcc35)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/d06842a8-3fda-4839-a785-df8421a39a97)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/da565508-f261-415a-b5d0-0f64121497ae)

Create Docker File and image

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/139474b4-608c-4af0-b2a7-784f2de2260a)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/6d0a2932-b20e-4652-9265-de0bc998ca2f)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/aaff8161-77dd-4357-a0c7-a6ff76ba2373)

Test in lambda console

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/d178aae7-b8bb-47a5-afe5-562e0d3d91ed)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/9a0736c6-5353-4a17-9d87-d523e4636908)

Create a trigger API Gateway HTTP API

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/7e24fcd1-dcc0-40b9-ae94-b696827c2e23)

# Code any Boto3

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/853778b4-0a37-467b-971c-82ab92d86cc2)

Create lambda role, and permissions full access EC2 and SNS

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/8fa2b65e-d38e-47be-80ed-dff234678140)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/a23f3e5c-562a-4646-ab7b-55467c3daf66)

# Configure Cloudwatch event rule

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/fee7ad64-2b68-4f1d-ae7c-f1d9fe0a548d)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/1e4aba9a-7ebe-4fa0-8fdf-578c8a3abbc7)

# Create lambda ec2_check_tags for trigger 

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/533a23d0-b75a-4fcd-b153-0c1460baeecc)

google boto3 ec2

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/956879b0-2262-4635-a71d-6983e05291d6)

and import function describe_tags

lambda finaly function

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/0548512b-d7ba-48ba-aec2-4ef07432b9f0)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/b19c585f-e416-4e8b-8535-690bcc743044)

test event lambda
![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/f3f5b855-fc11-4c65-abb0-ff838a1fa7d2)

Ec2 is running

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/031bb686-482f-467a-ad6a-3bfe327f3c46)





### lambda function ec2_check_tags

---
import json
import boto3

ec2client = boto3.client('ec2')
snsclient = boto3.client('sns')


def lambda_handler(event, context):
    # TODO implement
    #print(event)
    ec2_instance_id=event['detail']['instance-id']
    
    # Put Logic
    tag_response= ec2client.describe_tags(
    Filters=[
        {
            'Name': 'resource-id',
            'Values':[ec2_instance_id],
        },
    ],
    )
    
   # print(tag_response)

    alltags=tag_response['Tags']
    
    flag='STOP'
    for item in alltags:
        print(item['Key'])
        if item['Key']=='SPECIAL_EXCEPTION':
            flag='DONT_STOP'
            break
            
    print(flag)    
    
      # Decision Making
    
    if flag=='STOP':
        # STOP 
        ec2client.stop_instances(InstanceIds=[ec2_instance_id])
        
      # Send threating email
        snsarn='arn:aws:sns:us-east-1:944020312758:SNSTopicEC2State:8a21932e-3088-4291-81e4-02072d4666bc'
        errormsg="EC2 "+ ec2_instance_id + " stopped"
        snsresponse=snsclient.publish(TopicArn=snsarn,
                                Message=errormsg,
                                Subject='EC2 Violated Company Policy!!! Manager will be notified!!!')


    return {
        'statusCode': 200,
        'body': json.dumps('Hello from Lambda!')
    }


![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/49547ab8-e914-4ba0-856f-2d71296e3254)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/794ecb84-7a27-4888-b77a-5fba8b771a80)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/7999c7f9-33b9-44b0-b146-df8df2d73506)

![image](https://github.com/felixdagnon/Master-serverless-real-project/assets/91665833/15eef3ea-0066-4cbe-8673-587b85d0a1a8)





































































































































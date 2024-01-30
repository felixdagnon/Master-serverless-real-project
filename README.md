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





























































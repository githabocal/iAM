# iAM - Providing s3, Dynamo DB and API Gateway access in AWS

-   Head to users in iAM and add user names and select AWS access type as password and set a custom password for users and click ```Next:Permission```
-   Add users to a group is selected by default and click on ```create group```
-   Set a group name and click on ```create a policy``` and select policies as follows
```
    -   s3
    -   Dynamo DB
    -   API Gateway
```
-   In Actions, access level should be selected as ```Read``` for all policies
-   Resources should be selected as ```All resources```
-   Then click on the ```Next: Tags``` and set a policy name and complete to create a policy
-   Then add the created policy in group
-   At the end of the process, download csv file and share it with user
-   The user should be able to login with IAM credentials.

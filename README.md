# IAM (Identity and Access management)
# Identity managmaent : 
                        By using identity managment we are provide the user name and password.
# Access managmaent :                        
                       Acesss managament provide the access to the specifc services oin AWS.   
 # Advantages of IAM IN AWS:
                            By using IAM services if we read only permission to user by that user can't able to chanage anything .
                            we can set time to some services because for some services we need to pay so we can set time to user to access the services.
 # STEPS TO CREATE IDENTITY OR AUTHENTICATION IN IAM 
 * open your AWS account and login as root user
 * go to IAM serives and click in IAM services
 * click in user and create a user and given name to user
   ![create a user](https://github.com/user-attachments/assets/6ba71cf4-709a-44f9-884d-5c8835bfcb5e)
   In above image for that user1.0 we are just given only identity access.![Screenshot 2024-09-04 113315](https://github.com/user-attachments/assets/8c2073aa-9afe-4428-bf35-dad192474430)
   after create user we  get sgin into aws account as Iam user by using belown link.
   # https://682033489701.signin.aws.amazon.com/console
   affer click in above link it will take to iam login page their we need to enter
   1) user name : user 01
   2) pasword : riW1*W$Q
      ![Screenshot 2024-09-04 111546](https://github.com/user-attachments/assets/12c9fd56-c775-47df-a288-573f1375c491)
      the above image shown the console to IAM user
      * in user1.0 we have gave permission for
        1)ec2
        2)vpc
        3)s3
        note: in user 1.0 we gave only read permission.
  # steo to create Access managmaent
   Acesss managament provide the access to the specifc services oin AWS.   
   *login as root user
   *click on create user
   *now attach the polices directly![Screenshot 2024-09-04 113157](https://github.com/user-attachments/assets/17bec6a4-c17a-46ad-b863-cfea1a293429)
   in above image we can see login acces to IAM user.
   ![Screenshot 2024-09-04 113315](https://github.com/user-attachments/assets/8cfb5653-7da9-406d-a08d-0e1356bb4ec1)
the above images so the IAM Console
IN IAM console we acces only the  permission which we gave
# create a group 
In AWS a group is a collection of users that share the same set of permissions. Instead of assigning permissions to each individual user, you can assign them to a group and all users in that group will automatically have those permissions. This simplifies management by allowing you to control access for multiple users at once.
![Screenshot 2024-09-04 114333](https://github.com/user-attachments/assets/3e1f6c57-6980-42f5-96c2-3ce42b134147)
after a create a group we and user
![Screenshot 2024-09-04 114543](https://github.com/user-attachments/assets/e95d2891-1667-47d9-a577-86e29889d57e)
in the above image we have not created the user
we can see on user , now we need to add user.
![Screenshot 2024-09-04 114851](https://github.com/user-attachments/assets/e7f1cbda-efb9-42c1-8aa9-4b56dd70cb0a)
i have added 2 user to group
NOtE : the  permission which we gave to group the same  permission also added to user in group.





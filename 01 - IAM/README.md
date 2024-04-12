Step to configuration IAM permission following AWS Best Pratices

1. **Create an User**

In this step bellow we are going to create a new user with **Adm permission** by AWS Console.

Go to **IAM Dashboard** and click on the option **Users** in the left and click on **Create User**.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/6858d8e0-4ddf-4dc2-a37c-cb0e6bf37373)

Name this new user and assign an access type to grant **CLI Access permissions**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/fe7d6939-9be5-4204-9d9b-ab94acf64b7a)

Now, We need to assign **permission policies** to this new user. In this lab, we will set this new user with **AdministratorAccess.**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/8ff0f018-9f8b-4027-bed2-6465c0a30106)

We can add a lot of **tags** to specify wich team or role this new user will work as seen bellow.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/0a2c9cc3-00f5-4c5f-b108-534d8de93dbb)

Also is possible create a Group of users. Go to **User Groups** and click on **Create group**. After that give a name for this new Group, **Add users to the group** and **Attach permissions** policies as in step(1.x?)

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/58dd4f0b-7053-4776-b1a5-75259c24f9f2)

As a last step you should make your account security so you need add a MFA to this new account. Go to **Users** find your user and click on the menu **Security credentials** and look for **MFA** .
Now, assign MFA Device.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/2574f6a3-df65-4d01-bc6d-95b15d957ad2)

Give a name for this device and click on Next.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/5f514137-446d-4694-bb96-c514acd15a1b)

Now, use any Authenticator app such as Microsoft Authenticator, Google Authenticator or Auth to scan the QR Code and get the code and click on **Add MFA**.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/8d59f642-bdea-45ff-bf80-86e442f44b8a)


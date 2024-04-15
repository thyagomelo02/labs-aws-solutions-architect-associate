Step to create a bucket S3

1. Go to **Amazon S3** and click on **Create a bucket** and give a name for your bucket. Remember, bucket name **must be unique** within a global namespace.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/eedd1d65-2d2d-4cab-b21d-b002b65bf268)

At the first time we will not use ACLs so let the ACLs disable

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/cea11ec5-ce5c-4b71-990e-478349f64f1f)

Now **Block all public acess**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/d8fbb9f5-8f54-4582-bc9b-581f9e2a814e)

Let the other options be with default settings. Then, click on **Create bucket** and you will can see your bucket in the list.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/cedc5d48-d392-44f9-a1df-ae4a2e1ddccb)

Now, we are going store a object in the bucket. **Click on** the bucket that you have created after that go to **Upload** and finally drag and drop your file or folders.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/9afd936b-86d8-42f5-9e4f-2c3268ddc0d7)

You will be able to see your uploaded file in the list below.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/aa758336-1e67-4024-a45a-cd38bbe7227e)

So now we want to see our interstelar.png. **Click upon** this file and look for **Object URL** follow the link to see the image.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/983e3b69-651c-493e-b343-fb3ff3109200)

At this point, you will encounter an **AccessDenied** message as shown bellow. Is that because we haven't made bucket public

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/512bb08b-4d3e-41f8-89eb-6b6be0be6736)

So now we have to make public this bucket to be able to acess it content.
We can setting the bucket public with **ACLs** and using **Bucket Policies**

First go to bucket **Permissions** and click on edit in **Block public access(bucket settings)**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/eab6da97-cbfb-4db4-880e-5a3626e5d085)

Now uncheck the option **Block all public access**, **Save changes** and **Confirm**.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/78643898-d3a7-42bc-bbe9-19b925f668a0)

Now, we will see two forms to make public a S3 public.
First using ACL(Access Control List).

**NOTE**: A majority of modern use cases in Amazon S3 no longer require the use of ACLs.
Follow to more:https://docs.aws.amazon.com/AmazonS3/latest/userguide/about-object-ownership.html

Go to your file permissions and click on **owner enforced** the object is enable the **ACLs**
![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/48879c89-1ccd-402e-afa1-9aa6f5197ab9)

**Click on** ACLs Enable

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/eba40a3e-1581-4c6a-8092-bd27bb58da4b)

We need to make those files public one at a time. Now, go back to your file, check it, and click on Actions, then select **Make public using ACL**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/ba418807-1f67-4383-a70f-ac545a006d0f)

**Make Public**

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/c0548dc5-30af-41fc-9dcd-c81264af364d)

Then you can F5 your image page to see the image.

![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/61c68b4d-187d-4302-9a34-3ff25dfcabfe)

Another form to make public your bucket(recommended) is using Bucket Policies

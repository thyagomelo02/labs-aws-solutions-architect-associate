Step to enable Versioning in a S3 bucket

1. Go to your S3 bucket and click on **Properties**. Locate **Bucket Versioning** and proceed to edit it.

   ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/a44a2139-70c8-41bf-9910-c418db65d643)

2. Set as **Enable** the bucket versioning and click on Save changes

   ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/6dfb3e81-1a92-438c-9f0a-899fc614e1c0)

3. The bucket Versioning has been enable sucessfuly
   ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/7f2bfe81-1e38-45f5-a455-30044ba54528)

4. Now, let's test our object versioning. A new object has been uploaded in HTML format.
  ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/a04461a1-0dfc-490f-80ef-be3be43a97c9)

5. Let's make a simple modification, and 
  ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/30920186-ea95-418e-9d34-fc35e137161b)

6. then we'll observe its versioning.
  ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/86c5c91d-5c39-4609-8bca-7c88295ae6fe)

7. Even if we delete the object, we can still view its versioning.

   ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/3ec77cb1-ad4e-477c-9558-1e90c55c0ea0)

8. But at this point, the object will have a **Delete marker** associated with it.

   ![image](https://github.com/thyagomelo02/labs-aws-solutions-architect-associate/assets/31568098/ac011510-d34a-4585-9c44-34223127083b)

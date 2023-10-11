# S3Tasks-AlbTask
 * Created a S3 bucket, with no public access and uploaded files to the bucket 
1) Created S3 bucket
![Screenshot (234)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/8ea5361f-ec4b-4245-89fa-0b72dd63e25f)
2) Blocked Public access
![Screenshot (235)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/5a58925a-3339-4fb4-b28d-41173bbcd39b)
![Screenshot (236)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/abe8e93f-1578-4b89-b308-c1320b778c16)
3) Uploaded a text file 
![Screenshot (237)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/87c230ee-2595-4c4e-b433-d4e1fe278243)
![Screenshot (238)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/f642595b-e052-4484-ab13-a41a82d6b9d1)
![Screenshot (239)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/42bf86d4-bb63-4ef5-8ce2-a0db64cf0873)
![Screenshot (240)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/503922d1-31ce-48c8-8970-816ff3a7da76)
4) After clicking in to Object URL it has declined due to no public access but when we click open it will show the text file .
![Screenshot (241)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/363feae5-b39c-4edb-9ab2-483e553c2b15)

===================================================================================================================================================

* Launch two ec2-instances and connect it to a application load balancer, where the output traffic from the server must be an load balancer IP address

  1) Create 2 ec2 instances
![Screenshot (246)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/653c0ef3-f3a9-4637-9d25-1d61259c0cb1)
  2) Set the security group as SSh and http server and set the userdata for output
  ![Screenshot (247)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/1834f814-83fb-498f-87e3-b620a2cac17c)
  3) output from ip adress of each instances from userdata
     * First Instance
  ![Screenshot (248)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/23167e40-c12d-4fe0-be59-688cfed7ea11)
    * Second Instance
  ![Screenshot (249)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/4c1f3b0f-2d67-45a2-a0b8-c24d463cc0d9)


  4) Create the ALB with Security group as HTTP Allow and Create Target Group with register 2 instances
  ![Screenshot (250)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/544516c1-7493-4e88-b6f3-eeebc7a11826)
![Screenshot (253)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/5e51ca47-b4e0-4651-84f4-81821dbbdd41)
![Screenshot (256)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/105565f1-b13a-4907-a6bc-301f9d723281)
 5) ALB created
![Screenshot (257)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/7ffeed45-80fc-4178-ae78-fe944ebcd604)
  6) target group instance is healthy
     ![Screenshot (258)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/e51be7a6-17e1-45f4-8453-e9f96c9b74f2)
  7) From Alb Dns server Ip address
     albtask-804037160.ap-south-1.elb.amazonaws.com
     ![Screenshot (259)](https://github.com/cloudmoh/S3Tasks-AlbTask/assets/126796948/403e6589-057c-4fd4-897c-fb7621f10d79)




      


     





     

# implementation
- After writing the terraform files the we need plug-in of that perticular cloud provider,so 1st apply the following command in terminal for plug-in.
> terraform init

![terraform_init](https://user-images.githubusercontent.com/60148173/120933857-acac1280-c719-11eb-95ea-022de7265626.PNG)

- Then apply following command in terminal for launching the perticular resource like we are launching the vpc resource,after apply its ask for confirm so we write yes option for forword the process other wise we can quite also.
> terraform apply

![terrform_apply](https://user-images.githubusercontent.com/60148173/120933515-2511d400-c718-11eb-9604-3ef8092625d0.PNG)


![create_vpc](https://user-images.githubusercontent.com/60148173/120933568-54284580-c718-11eb-86e2-e4279847c1f8.PNG)

- So after creating the vpc in aws using terraform,we can verify wheather it is launch or not so following  image show our VPC is launch.

![In_console_check_vpc](https://user-images.githubusercontent.com/60148173/120933626-93ef2d00-c718-11eb-8299-5349546698c2.PNG)

![create_two_subnet](https://user-images.githubusercontent.com/60148173/120933608-85087a80-c718-11eb-9045-44a57720d735.PNG)

![IG](https://user-images.githubusercontent.com/60148173/120933624-93569680-c718-11eb-910d-f8545f65a071.PNG)

![routetable](https://user-images.githubusercontent.com/60148173/120933630-95b8f080-c718-11eb-84c3-9442f46ab563.PNG)

## Destroy Created Resource 

- The `terraform destroy` command is a convenient way to destroy all objects managed by a particular Terraform configuration. Following command is used to destroy the resources. within a sec it remove all the resources
> terrafom destroy
![destroy](https://user-images.githubusercontent.com/60148173/120933615-8a65c500-c718-11eb-8a2a-b29f3c90c467.PNG)

![destroy_vpc](https://user-images.githubusercontent.com/60148173/120933620-8fc30f80-c718-11eb-9c20-ac6e1fc7d761.PNG)

![no_vpc_in_console](https://user-images.githubusercontent.com/60148173/120933628-9487c380-c718-11eb-888c-4a74e84cb665.PNG)




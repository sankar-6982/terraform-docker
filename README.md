**Deploying application using Terraform:**

Cloned the repo into my local and got into the directory.

<img width="940" height="201" alt="image" src="https://github.com/user-attachments/assets/b6e1c435-fa0f-40ac-8227-71a0bb865e1b" />


Created .env file and dockerfile for the cart service:

<img width="876" height="164" alt="image" src="https://github.com/user-attachments/assets/7c23a8bb-1a88-4cf3-a7c7-3cc049410a79" />


<img width="940" height="302" alt="image" src="https://github.com/user-attachments/assets/c7b9733b-cb82-4c07-8eeb-3c8ce33a4e81" />

Created docker network to test it in my local.

<img width="940" height="67" alt="image" src="https://github.com/user-attachments/assets/b92fe1ca-548e-419a-b138-8cdf3dfbe107" />

Created mongo db container:

<img width="940" height="56" alt="image" src="https://github.com/user-attachments/assets/675f5576-258b-407c-95d4-7bf56c07d4b2" />

Created the container for cart service:

<img width="940" height="59" alt="image" src="https://github.com/user-attachments/assets/0940027a-d3c7-47dc-92af-cabd2c8a0603" />

In the same way created containers for all the other services.

<img width="940" height="203" alt="image" src="https://github.com/user-attachments/assets/416feb95-d2dc-4300-9bd1-fb86b73cd020" />

Checked if the application is working fine.

<img width="940" height="383" alt="image" src="https://github.com/user-attachments/assets/77a4586e-e88b-4b99-b1af-f425b50a76cc" />

Did tagging and pushed it into docker hub:

<img width="940" height="431" alt="image" src="https://github.com/user-attachments/assets/27c43f99-d183-4d8e-bd4e-14d9f054ce05" />

<img width="940" height="174" alt="image" src="https://github.com/user-attachments/assets/00ed4425-f8a7-43ea-976d-5205ace60f39" />

**Terraform creation:**

Created main.tf and output.tf file:

<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/7771b5c0-451b-45f7-baf0-9fce5c6a7a7a" />

Initialized the environment:

<img width="940" height="552" alt="image" src="https://github.com/user-attachments/assets/30532e52-be9a-441f-a77d-681daec33aa6" />

Validated the code:

<img width="915" height="125" alt="image" src="https://github.com/user-attachments/assets/86a12684-d5de-45d3-8886-3e812f3a3ee8" />

Ran the command to deploy:

<img width="940" height="556" alt="image" src="https://github.com/user-attachments/assets/fab63828-2372-45e9-ad3f-bb14773b63e5" />

Received the output:

<img width="940" height="506" alt="image" src="https://github.com/user-attachments/assets/1e8829df-e1ef-4514-b2f0-12565e7eb7d0" />

Verified the instance from console:

<img width="940" height="102" alt="image" src="https://github.com/user-attachments/assets/12c52e84-857d-445e-999c-24632fe3ea9e" />

Verified the application using the public IP:

<img width="940" height="366" alt="image" src="https://github.com/user-attachments/assets/eb7632ba-2342-431b-badf-d844ac42780f" />

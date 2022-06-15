### DOCUMENTING MY CLOUD PROGRESS.

<!--
**ay099/ay099** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns:  
- ⚡ Fun fact: ...
-->

### JUNE 07, 2022: What they call baby steps?
--- 
On this day, after weeks of preparation, I passed my AZ-900 exam and got my first ever cloud certificate, **The Microsoft Azure Fundamentals**. 

## JUNE 09, 2022: First Project
---
Having passed the AZ-900, I basically googled projects that I could build (to make the theories and azure services that I had studied for the exam) stick. I came across the [Cloud Resume Challenge](https://cloudresumechallenge.dev/) and hopefully by the time you read this, you should be able to see that I've completed the challenge in this repo right here on my account and you should check it for more details on this. [My Cloud Resume Challenge](https://github.com/ay099/my-azure-resume)

## JUNE 14, 2022: Is this how hackers feel?
---
As part of the preparation for the AZ-900, I learnt about other ways of without necessarily accessing the azure portal. One way is to use the Azure Cloud Shell, or to locally install the Azure CLI or Powershell on your computer. I had never really gone deep into this when preparing because I didn't have to but today I took upon myself to. I realized alot of cloud admins and other related occupations interact with cloud without really using the UI.

I installed the CLI on my system and having a little expereince with bash helped me with the learning curve when reading the CLI documentation. After reading the documentation, I performed the following actions using the CLI:

- I logged into my azure account
![Screenshot (19)](https://user-images.githubusercontent.com/75920830/173904789-a12e31f9-a3a8-419b-ae91-ecc65986919d.png)

- I created a resource group called "myclirg" in "eastus"
![Screenshot (20)](https://user-images.githubusercontent.com/75920830/173905560-b308c60a-303a-4372-806b-98b1e44cf4e2.png)

- I created a lock for the "myclirg" resource group of type "cannot delete" named "deleteprooflock". A lock helps to foolproof the safety of a resource scope. This is to prevent users from either accidentally deleting the resource group (delete lock) or accidentally performing any other action asides being able to view resources in the resource group (read-only lock)
![Screenshot (21)](https://user-images.githubusercontent.com/75920830/173906670-380121ae-841f-4d65-9ab9-d1ff352ca20c.png)

- Fully knowing that I had created a delete lock for the resource group, I tried to delete the resource group to see it's powers
![Screenshot (22)](https://user-images.githubusercontent.com/75920830/173907460-397ced8f-8720-4b0d-ba92-c72f5aa1309a.png)
The lock worked, Mission failed successfully 👌

- I deleted the resource group lock and then deleted the resource group.

![Screenshot (24)](https://user-images.githubusercontent.com/75920830/173908349-686f3556-83a1-4dc7-b213-7ec2c6ae383b.png)





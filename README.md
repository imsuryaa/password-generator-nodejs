# Random password generator with NodeJS

To use this project, Clone this repo and type `npm install` in the CLI

To run this project, you need to type `node index` in the CLI and you will be getting the random password

![random-password](https://user-images.githubusercontent.com/45379824/124947735-bb922780-e02d-11eb-8ca4-6a9653b9a1dc.PNG)

To generate the password based on the specific properties, please find below commands
- `node index --length=14` to generate 14 character length random password, by default character length is 8
- `node index -nn` to generate the random password without numbers
- `node index -ns` to generate the random password without symbols
- `node index --save` to save generated passwords to password.txt file, this file will automatically created in root folder.

Here's the screenshot for reference.

![cli-ss](https://user-images.githubusercontent.com/45379824/124949159-f21c7200-e02e-11eb-8f99-15d8bd5f93f6.png)

passwords.txt - demo file generated with random passwords

![textfile-ss](https://user-images.githubusercontent.com/45379824/124949453-3445b380-e02f-11eb-9c4c-365352f681f3.png)

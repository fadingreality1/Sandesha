
# Sandesha Chat Application

Sandesha is a real-time chat application developed using Django Channels, WebRTC, Django Rest Framework, React, MySQL, and AES encryption. It provides users with a seamless and secure platform for one-on-one messaging, group chats, video calls, and social interactions.




## Features

- #### Real-time Messaging:
Instant messaging using Django Channels for a smooth communication experience.

- #### Video Calls:
WebRTC integration enables high-quality video calls directly within the app.
- #### One-on-One Chats:
Private conversations between users for confidential communication.
- #### Social Feed:
Users can post pictures, like, comment, and delete posts on the feed page.
- #### Welcome Emails:
Automated welcome emails sent to new users using the SMTP protocol.
- #### End-to-End Encryption:
AES algorithm ensures secure and private messaging.
- #### MySQL Database:
Efficient data storage and management with MySQL.
- #### Django Rest Framework:
Backend infrastructure built using DRF for robust API development
- #### React UI:
Responsive and intuitive user interface developed with React.


## Run Locally

Clone the project

```bash
git clone --recursive https://github.com/fadingreality1/sandesha.git
```

Go to the project server directory

```bash
cd "sandesha/server"
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver 7890
<# By now your Backend server will be running at port 7890 #>
```

Go to the project client directory

```bash
cd ..
cd client
npm install
npm start
```

## Usage/Examples

- Access the application at http://localhost:8000/.
- Create an account or log in if you already have one.
- Explore the chat features, social feed, and video calling functionality.


## Screenshots

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/41f53f38-eeee-4ba8-9ff0-486b56da6553)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/68562974-45b2-4813-9ca3-ab5c4d5b2f6b)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/d7490213-5533-4151-a07f-e059ccc275ff)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/6b92faf0-90d1-4eee-a676-48980a6cbb31)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/1f93e482-e0ab-4398-ae1f-d82916afbfd5)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/41f53f38-eeee-4ba8-9ff0-486b56da6553)

![image](https://github.com/fadingreality1/Lazy_coder/assets/114291201/6facf0e6-5912-4252-b317-ce3a3fe51dab)
## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.


## Authors

- [Kunal Verma](https://github.com/fadingreality1)
- [Aman Kumar srivastava](https://github.com/Aman1807-coder)


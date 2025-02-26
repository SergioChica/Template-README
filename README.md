# Project Name

Is a platform designed for secure and efficient data management. It features user authentication, an admin panel, and advanced search capabilities. Built with FastAPI, Django, and React, it supports PostgreSQL and MySQL, ensuring scalability and reliability.

## Main Features
- > Authentication with JWT
- > Administration panel
- > Advanced search

## Logo
![Project logo](https://res.cloudinary.com/dlezql4zq/image/upload/v1740598704/iiac_vtlq3l.png)



## Technologies Used
### Backend
- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) Python  
- ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) FastAPI  
- ![Django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white) Django  

### Frontend
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) HTML  
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) CSS  
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) React  

### Database
- ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) PostgreSQL  
- ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) MySQL  

### Security
- ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) JWT  
- ![OAuth](https://img.shields.io/badge/OAuth-1E90FF?style=for-the-badge) OAuth  



## Optional Extensions
| Extensión | Descripción |
|-----------|------------|
| [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | Helps maintain a clean and error-free code. |
| [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | Automatic code formatter. |
| [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) | Allows API testing directly from VS Code. |

## Deployment
- > Render: SQL Services
- > Docker: Backend container:latest

## Project Structure
```Bash
    project
    ├── src
    │   ├── controllers
    │   ├── models
    │   ├── routes
    │   ├── services
    │   ├── main.py
    ├── config
    ├── public
    ├── tests
    ├── .env.example
    ├── requirements.txt
    ├── package.json
    └── README.md

```

## Installation and configuration
1. **Clone this repository**
```bash
    git clone https://github.com/user/project-name.git
    cd project-name
```
2. **Install dependencies**
```bash
    npm install         # Node.js
    pip install -r requirements.txt  # Python
``` 
3. **Setting environment variables**
```bash
    cp .env.example .env 
``` 
4. **Running the application**
```bash
    npm run dev         # Node.js
    python main.py      # Python
``` 

## API Endpoints
| Method  | Endpoint | Description | 
| ------------- | ------------- | ------------- |
| `GET`  | `/api/data`  | Gets the list of data |
| `POST`  | `/api/auth/login`  | User authentication |
| `PUT`  | `/api/data/:id`  | Update the data of a piece of information |
| `DELETE`  | `/api/data/:id`  | Deletes a piece of data |

## Cron Jobs
| Task  | frequency | Description | 
| ------------- | ------------- | ------------- |
| Execute Program  | `30 22 * * 1-5 /restart.sh`  | 	Runs at 10:30 PM Monday through Friday. |
| Delete Temporary Files  | `0 7 * * * rm -rf /tmp/*`  | Delete temporary files every day at 7 AM. |
| synchronization with database  | `0 6,18 * * * /home/user/sync_db.sh`  | Synchronize the database every day at 6 AM and 6 PM. |

## Dependencies
### Node.js
- > Dependency file: package.json
```json
{
  "dependencies": {
    "express": "^4.18.2",
    "mongoose": "^7.2.1",
    "dotenv": "^16.0.3"
  },
  "devDependencies": {
    "typescript": "^5.1.3",
    "nodemon": "^2.0.22"
  }
}
``` 
### Python
- > Dependency file: requirements.txt
```py
flask==2.2.3
requests==2.28.1
pandas==1.5.3
``` 

## Authors
Sergio - [GitHub](https://github.com/SergioChica)

## License
 This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.

- > Create a new branch (git checkout -b feature-branch).

- > Commit your changes (git commit -m "Add new feature").

- > Push to the branch (git push origin feature-branch).

Open a pull request.
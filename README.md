# AaruChatBot

AaruChatBot is a conversational AI bot designed to interact with users and perform various tasks. This project includes the bot's configuration, deployment scripts, and other necessary files to get it running.

## Features

- Interactive chatbot with various functionalities
- Docker support for containerization
- Easy deployment with Heroku

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/itzAsuraa/AaruChatBot.git
    cd AaruChatBot
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Configure the environment variables:
    - Copy `sample.env` to `.env` and fill in the necessary values.

## Usage

To start the bot locally:
```sh
python3 -m Aaru
```

# Deployment

## Docker 
  
  Build and run the Docker container:
```sh
docker build -t aaru-chatbot .
docker run -d -p 8000:8000 aaru-chatbot
```
## Heroku

1. Install the Heroku CLI and log in:
```sh
heroku login
```
2. Create a new Heroku app:
```sh
heroku create Aaru
```
3. Deploy the app:
```sh
git push heroku main
```

# Contributing

Feel free to fork this repository, make feature branches, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

# Contact

<a href="https://t.me/itzAsuraa"><img title="Telegram" src="https://img.shields.io/badge/Telegram-%23000000.svg?&style=for-the-badge&logo=telegram&logoColor=61DAFB"></a>
<a href="https://instagram.com/itz_Asuraa"><img title="Instagram" src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>


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

## Deployment

# Docker 
  
  Build and run the Docker container:
```sh
docker build -t aaru-chatbot .
docker run -d -p 8000:8000 aaru-chatbot
```





# Dream Machine API

A Python script to generate videos using the Dream Machine API and fetch the latest generated video link.

## Features

- Generate videos via Dream Machine API.
- Asynchronously check for video generation status.
- Output the latest generated video link.

## Prerequisites

- Python 3.7+
- `requests`
- `aiohttp`

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/danaigc/DreamMachineAPI.git
    cd DreamMachineAPI
    pip install -r requirements.txt
    ```
   login https://lumalabs.ai/dream-machine/

   Get your accessToken here
  ![WechatIMG4170.jpg](https://s2.loli.net/2024/06/13/Cd6gQ4AaZKGNb3r.png)
2. Create a virtual environment and activate it (optional):
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install requests aiohttp
    ```
## Configuration

1. **Create a `config.json` file**

    The `config.json` file should be in the root directory of the project. Here is a sample configuration:

    ```json
    {
    "use_proxies": true,
    "auto_complete_task": true,
    "auto_play_game": true,
    "account_delay": 5,
    "game_delay": 3,
    "wait_time": 3600,
    "data_file": "data.txt"
    }

    ```

    - `auto_complete_task`: Whether to automatically complete tasks.
    - `auto_play_game`: Whether to automatically play the All Game.
    - `account_delay`: Delay between processing each account (in seconds).
    - `wait_time`: Delay between processing all accounts (in seconds).
    - `game_delay`: Delay between processing for Each Game (in seconds)
    - `data_file`: File containing account data.

2. **Create a `proxies.txt` file**

    The `proxies.txt` file should be in the root directory and contain a list of proxies in the format `username:password@host:port`.

    Example:

    ```
    user1:pass1@ip1:port1
    user2:pass2@ip2:port2
    ```

3. **Create a `data.txt` file**

    The `data.txt` file should be in the root directory and contain one account per line.

    Example:

    ```
    query1
    query2
    ```

## Usage

To run the bot, execute the following command:

```bash
python bot.py
```
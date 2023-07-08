# Twitter API Project

This project demonstrates the usage of the Twitter API using the Tweepy library in Python. It covers various functionalities such as authentication, updating status, retrieving timelines, interacting with tweets, following users, and implementing pagination.

## Prerequisites

To run this project, you'll need:

- Python 3.6 or higher
- Tweepy library
- Twitter API credentials (API key, API secret key, Access token, Access token secret)

## Installation

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/twitter-api-project.git
   ```

2. Navigate to the project directory:
   ```
   cd twitter-api-project
   ```

3. Install the required dependencies by running the following command:
   ```
   pip install tweepy
   ```

## Configuration

1. Open the `config.py` file in a text editor.

2. Replace the placeholders with your Twitter API credentials:
   ```python
   consumer_key = 'YOUR_CONSUMER_KEY'
   consumer_secret = 'YOUR_CONSUMER_SECRET'
   access_token = 'YOUR_ACCESS_TOKEN'
   access_token_secret = 'YOUR_ACCESS_TOKEN_SECRET'
   ```

## Usage

The project is organized into separate Python scripts for each functionality. Here's an overview of what each script does:

### 1. Authentication

- Script: `authentication.py`
- Description: Demonstrates how to authenticate and establish a connection to the Twitter API using your credentials.
- Usage: Run the script using the following command:
  ```
  python authentication.py
  ```

### 2. Update Status

- Script: `update_status.py`
- Description: Shows how to post a new tweet/status on your Twitter account.
- Usage: Run the script using the following command:
  ```
  python update_status.py
  ```

### 3. My Timeline & User Timeline

- Script: `timeline.py`
- Description: Retrieves the recent tweets from your timeline or a specific user's timeline.
- Usage:
  - To fetch tweets from your timeline, run the script with no arguments:
    ```
    python timeline.py
    ```
  - To fetch tweets from a specific user's timeline, pass the username as an argument:
    ```
    python timeline.py username
    ```

### 4. Interacting with Tweets

- Script: `interact_with_tweets.py`
- Description: Demonstrates how to interact with tweets, such as liking, retweeting, and replying to tweets.
- Usage: Run the script using the following command:
  ```
  python interact_with_tweets.py
  ```

### 5. Follow Users

- Script: `follow_users.py`
- Description: Illustrates how to follow/unfollow users on Twitter.
- Usage: Run the script using the following command:
  ```
  python follow_users.py
  ```

### 6. Items & Pagination with Tweepy

- Script: `pagination.py`
- Description: Implements pagination to retrieve items (tweets, followers, etc.) in batches using Tweepy.
- Usage: Run the script using the following command:
  ```
  python pagination.py
  ```

Feel free to explore each script and modify them according to your specific requirements.

## Resources

- Tweepy Documentation: [https://docs.tweepy.org/](https://docs.tweepy.org/)
- Twitter API Documentation: [https://developer.twitter.com/en/docs/twitter-api](https://developer.twitter.com/en/docs/twitter-api)

Please refer to the above resources for detailed information about Tweepy and the Twitter API.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.

**Note:** Be aware of the Twitter API usage limits and comply with their guidelines while using this project.

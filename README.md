# AW Metatrader to Telegram MT5

The **AW Metatrader to Telegram MT5** is an automated forex software developed by Forex Robot Easy Team. This software provides efficient trading notifications by sending them directly to subscribers through the Telegram messenger.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/aw-metatrader-to-telegram-mt5-review-and-download-the-automated-forex-software-for-efficient-trading-notifications/). Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.

## How it Works

The code provided here showcases the basic functionality of the **AW Metatrader to Telegram MT5** software. Let's go through the different sections of the code to understand how it works:

### Variables

The code defines several necessary variables:

- `apiKey`: A string variable to store the API key required for sending messages through the Telegram messenger.
- `chatId`: A string variable to store the chat ID of the subscribers to whom the notifications will be sent.
- `notificationText`: A string variable to store the formatted notification messages.
- `screenshotWidth` and `screenshotHeight`: Integer variables to define the width and height of the captured screenshots.

### Trading Functions

The code defines the following trading functions:

- `RetrieveTradingEvents()`: This function retrieves trading events from the trading terminal.
- `FormatNotificationMessages()`: This function formats the trading events into notification messages and returns the formatted messages.
- `SendNotificationMessages()`: This function sends the notification messages to subscribers via the Telegram messenger.

### Setup Interface

The code defines the `SetupInterface()` function, which creates a user-friendly interface for setting up the utility. This function can be customized to suit the specific requirements of the users.

### Adjustable Screenshots

The code defines the following functions related to adjustable screenshots:

- `CaptureScreenshots()`: This function captures screenshots of the trading events.
- `AdjustScreenshots()`: This function allows users to adjust the captured screenshots before sending them.

### Customizable Notification Text

The code defines the following functions related to customizable notification text:

- `ReceiveUserInput()`: This function receives user input for customizing the notification text.
- `IncludeEmoji()`: This function allows users to include emoji in the notification messages.

### Main Function

The `OnStart()` function is the main function of the code. It executes the following steps:

1. Calls the `SetupInterface()` function to set up the utility.
2. Calls the `RetrieveTradingEvents()` function to retrieve trading events.
3. Formats the trading events into notification messages by calling the `FormatNotificationMessages()` function and stores the formatted messages in the `notificationText` variable.
4. Calls the `CaptureScreenshots()` function to capture screenshots of the trading events.
5. Allows users to adjust the captured screenshots by calling the `AdjustScreenshots()` function.
6. Sends the notification messages to subscribers by calling the `SendNotificationMessages()` function.

This code serves as a reference and can be customized and extended as per the specific requirements of the users.

For more details about the product and to access its official developer, please visit the [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/aw-metatrader-to-telegram-mt5-review-and-download-the-automated-forex-software-for-efficient-trading-notifications/) website.

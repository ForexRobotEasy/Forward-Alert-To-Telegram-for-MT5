# Forward Alert To Telegram for MT5

This code is a custom script for MetaTrader 5 (MT5) that allows the user to forward pop-up alerts to a Telegram channel or group. It captures a screenshot of the alert and sends it along with the alert details to the specified Telegram channel/group.

## Features
- Forward pop-up alerts to Telegram
- Capture screenshot of the alert
- Include alert details in the Telegram message

## External Dependencies
- TelegramAPI.mqh: This library provides the necessary functions to interact with the Telegram API.
- WinUser32.mqh: This library allows capturing screenshots using the WinUser32 library.

## Global Variables
- `apiKey`: Replace with your Telegram API key.
- `channelId`: Replace with your Telegram channel/group ID.
- `forwardAlerts`: Enable/disable forwarding of alerts.

## Custom Functions
- `ForwardAlertToTelegram`: Forwards the alert details to Telegram, including a captured screenshot.
- `CaptureScreenshot`: Captures a screenshot of the alert.
- `OnAlert`: Handles pop-up alerts and calls the `ForwardAlertToTelegram` function.
- `OnInit`: Initializes the script and registers the `OnAlert` function as the handler for pop-up alerts.
- `OnDeinit`: Deinitializes the script and unsubscribes from pop-up alerts.
- `OnTimer`: Handles timer events and checks for new pop-up alerts.
- `OnStart`: Empty function, not used in this script.

## Product Description
Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code that can work with this product as described.

[Forward Alert To Telegram for MT5](https://forexroboteasy.com/forex-robot-review/forward-alert-to-telegram-for-mt5-in-depth-review-real-results/) is a script developed by the Forex Robot Easy Team. This script allows you to forward pop-up alerts from your MT5 platform to a Telegram channel or group.

With this script, you can receive real-time notifications of pop-up alerts directly on your Telegram channel or group, ensuring you never miss any important trading signals. The script captures a screenshot of the alert and sends it along with the alert details to the specified Telegram channel/group.

To use this script, you need to have a Telegram API key and the ID of your desired Telegram channel/group. After replacing the `apiKey` and `channelId` variables with your own values, you can enable or disable the forwarding of alerts by setting the `forwardAlerts` variable accordingly.

Please note that this script requires the external dependencies `TelegramAPI.mqh` and `WinUser32.mqh`. Make sure to include these libraries in your MT5 platform before using the script.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Forward Alert To Telegram for MT5](https://forexroboteasy.com/forex-robot-review/forward-alert-to-telegram-for-mt5-in-depth-review-real-results/).

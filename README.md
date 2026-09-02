<div align="center">

# Spend less on OpenRouter models

OpenRouter Widget for macOS tracks prices that change hour by hour, catches discounts, and helps you switch before extra spend adds up.

[![Download latest version](https://img.shields.io/badge/Download-latest%20version-F59E0B?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/AlexProUX/or_widget/releases/latest/download/OpenRouterWidget.app.zip)

![macOS 13+](https://img.shields.io/badge/macOS-13%2B-2F2F2F?style=flat-square&logo=apple&logoColor=white)
![Apple silicon](https://img.shields.io/badge/Apple%20silicon-native-2F2F2F?style=flat-square)

<br>

<img src="assets/openrouter-widget.png" alt="OpenRouter Widget showing discounted models, context sizes, token prices, and discounts" width="390">

</div>

## Why it exists

OpenRouter pricing is not something you can check once and forget. A model that fits your budget today can cost more tomorrow, while a cheaper alternative or a new discount appears elsewhere.

OpenRouter Widget keeps current context sizes, input/output prices, and discounts in the macOS menu bar. It helps you spot a better offer quickly, copy its model ID, and switch before unnecessary API costs accumulate.

- **Stay on top of price changes:** the widget refreshes when opened and every 15 minutes.
- **Find better offers:** compare Discounts, Top weekly, and New from the menu bar.
- **Read the real cost quickly:** see context size and input/output token prices in every model card.
- **Sort for savings:** order models by name, price, discount, rating, or release date.
- **Switch in one click:** copy an identifier such as `openrouter/z-ai/glm-5.3-flash` directly into your configuration or agent instructions.
- **Keep useful data available:** the widget preserves the last known good list when a source temporarily fails.
- **Stay current:** new widget releases are detected automatically and installed from GitHub.

The app lives entirely in the menu bar and does not add an icon to the Dock.

## Download and install

1. [Download the latest `OpenRouterWidget.app.zip`](https://github.com/AlexProUX/or_widget/releases/latest/download/OpenRouterWidget.app.zip).
2. Double-click the archive to extract `OpenRouterWidget.app`.
3. Move the app to the **Applications** folder.
4. On first launch, Control-click the app and choose **Open**.
5. If macOS still blocks it, open **System Settings → Privacy & Security**, choose **Open Anyway**, and confirm.

### Requirements

- macOS 13 or later
- Apple silicon Mac

## Using the widget

- **Left-click** the OpenRouter menu-bar icon to open or close the widget.
- Choose **Discounts**, **Top weekly**, or **New**, then use the sort menu to reorder the current list.
- Click any model card to copy its ready-to-paste OpenRouter identifier.
- **Right-click** the menu-bar icon to see the installed version, install an available update, or quit.
- Use the refresh button to request fresh model data at any time.

## Updates

The widget checks GitHub Releases at launch and every three hours. When a newer version is available, an orange **Update** button appears in the widget and an **Update** action appears in the right-click menu.

You can also browse or download every published build from the [Releases page](https://github.com/AlexProUX/or_widget/releases).

## Version history

| Version | Highlights |
| --- | --- |
| [0.1.2](https://github.com/AlexProUX/or_widget/releases/tag/v0.1.2) | Removed focus-ring artifacts across the widget and refined the Update control. |
| [0.1.1](https://github.com/AlexProUX/or_widget/releases/tag/v0.1.1) | Initial focus-state hotfix for the tab control. |
| 0.1.0 | Initial packaged preview with model tabs, sorting, clipboard copy, caching, and in-app updates. |

## Notes

Model availability, prices, context sizes, discounts, and rankings come from OpenRouter and may change over time. OpenRouter Widget is an independent companion app and is not affiliated with OpenRouter.

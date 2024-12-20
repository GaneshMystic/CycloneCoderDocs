---
title: Configuration
weight: 1
next: "docs/guide"
---

Please check out the [installation guide](/docs/Installation) and [getting started](/docs/getting_started) before configuring the addon.

This pages covers `settings` and `options` that can be altered to make good use of the extension. See advanced use case to add more models or configure new providers.

<div class="hx-mt-6"></div>
<img width="100%" style="border-radius:8px; overflow:hidden" src="/images/gif/quick-settings.gif" />

## Chat Settings

You can change or update the `API key` by clicking the api key button on top right corner of chat window anytime.

{{< callout type="info" >}}
Mistral will use the same key provided for chat.
{{< /callout >}}

Use `{{< icon "dots-vertical" >}}` button on the top right corner opens additional chat settings where you can update few more settings.

1. You can change the Provider `API URL`.
2. `Chat context` allows you to say the number of latest `chats` from current history to used.
   {{< callout type="warning" >}}
   Both the user and assistant chats are counted while considering the chat history.
   {{< /callout >}}
3. Input tokens will represent number of tokens that gets used as context for generating response of each chat.
4. Number of `new tokens` that get generated on each response.

{{< callout type="info" >}}
Decrease Tokens to generate will generate short but quick AI response.
{{< /callout >}}

## Inline Completion

1. Press `Ctrl + Shift + A` to open the chat interface.
2. Click the `Code Complete` button on bottom bar to open settings.
3. Enable `code completion check box` to activate inline code suggestions.
4. Select the `Completion Provider` and the available `code completion model`.

{{< callout type="warning" >}}
Mistral code complete model will use the same key provided for the chat.
{{< /callout >}}

1. Code temperature will change the `creativity` of the suggestion model.
2. Timing will the `wait time` before each trigger of completion.

## Questions or Feedback?

{{< callout type="error" emoji="🐞" >}}
Cyclone Coder is still under development, and your input is valuable!
Have a question or feedback? Feel free to [open an issue](https://github.com/GaneshMystic/CycloneCoderDocs/issues)!
{{< /callout >}}

[`{{< icon "pencil" >}} Edit this page`](https://github.com/GaneshMystic/CycloneCoderDocs/edit/main/content/docs/extension/configuration.md)

---
title: Inline Code Suggestion
weight: 3
---

## Modes

Check the bottom bar for the modes of inline code suggestion system.

1. `{{< icon "ban" >}} Code Complete` will be displayed if code completion is disabled.
2. `{{< icon "check" >}} Code Complete` will show that the completion is active.
3. `{{< icon "exclamation" >}} Code Complete` states there is some error in connection.

## Configuration

Click on the `Code Complete` button on bottom bar to open the settings.

1. Ollama and mistral are the only providers that support code completion for now.
2. Set the `Max Tokens` to limit the length of code completion that gets generated.
3. Increase the `Temperature` of make the model generate more creative suggestions.
4. `Timing` will allow you to set the delay to trigger new suggestion generation. Decreasing the Timing value will make it more responsive by triggering suggestions faster.


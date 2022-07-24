---
description: Iframe widget is used to display iframes in your app.
---

# Iframe

![](<../../.gitbook/assets/cleanshot-2021-07-04-at-23.03.52 (1).gif>)

### Properties

| Property          | Description                                                         |
| ----------------- | ------------------------------------------------------------------- |
| **source**        | Sets the URL of the page to embed.                                  |
| **title**         | Labels the content of the page to embed.                            |
| **borderColor**   | Sets the color of the border surrounding the page to embed.         |
| **borderOpacity** | Sets the color opacity of the border surrounding the page to embed. |
| **borderWidth**   | Sets the width of the border surrounding the page to embed.         |

### Events

| Action                | Description                                                                                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **onURLChanged**      | Sets the action to be run when the source url is changed. See a list of [supported actions](../appsmith-framework/widget-actions/).                              |
| **onMessageReceived** | Sets the action to be run when a postMessage event is received from the embedded page. See a list of [supported actions](../appsmith-framework/widget-actions/). |
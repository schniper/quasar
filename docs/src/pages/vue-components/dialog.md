---
title: Dialog
---

Quasar Dialogs are a great way to offer the user the ability to choose a specific action or list of actions. They also can provide the user with important information, or require them to make a decision (or multiple decisions).

From a UI perspective, you can think of Dialogs as a type of floating modal, which covers only a portion of the screen. This means Dialogs should only be used for quick user actions, like verifying a password, getting a short App notification or selecting an option or options quickly.

::: tip
Dialogs can also be used as a globally available method for more basic use cases, like the native JS alert(), prompt(), etc. For the latter behaviour, go to [Dialog Plugin](/quasar-plugins/dialog) page.
:::

::: tip
When the user hits the phone/tablet back button (only for Cordova apps), the Dialog will be closed automatically. Also, when on a desktop browser, hitting the `ESCAPE` key will also close the Dialog, as does clicking or touching outside of the Dialog, unless configured otherwise.
:::

## Installation
<doc-installation components="QDialog" directives="CloseDialog" />

## Usage
<doc-example title="Basic" file="QDialog/Basic" />

<doc-example title="Styling" file="QDialog/Style" />

### Positioning
<doc-example title="Positions" file="QDialog/Positioning" />

<doc-example title="Maximized" file="QDialog/Maximized" />

### Various Content
Dialogs can contain any content. Some examples:

<doc-example title="Various Content" file="QDialog/VariousContent" />
<doc-example title="With Containerized QLayout" file="QDialog/Layout" />

### Handling Scroll
<doc-example title="Scrollable Dialogs" file="QDialog/Scrollable" />

### Different Modes
User cannot dismiss the Dialog by pressing ESCAPE key or by clicking/tapping on its backdrop.
<doc-example title="Persistent" file="QDialog/Persistent" />

Dialogs can also be a part of the page, without requiring immediate focus. It's where "seamless" mode comes into play:
<doc-example title="Seamless" file="QDialog/Seamless" />

### Dialog in Dialog
You are able to open dialogs on top of other dialogs, with infinite number of depth levels.
<doc-example title="Inception" file="QDialog/Inception" />

### Sizing
You are able to customize the size of the Dialogs. Notice we either tamper with the content's style or we use `full-width` or `full-height` props:
<doc-example title="Sizing examples" file="QDialog/Sizing" />

## API
<doc-api file="QDialog" />

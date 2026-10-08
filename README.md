# UXMachine plugin

Measure a web page in a real browser and get verifiable observations, with their evidence and limits.

This repository holds only the plugin: the skill and the connector configuration. UXMachine itself is a hosted service at https://uxmachine.app.

## What it does

UXMachine measures what a page shows when it loads, at 1280×800 and 390×844 and on up to 11 pages of the site. Only checks with an exact state that can be measured again the same way come out through this connector; the list is at https://uxmachine.app/en/agents/rules. Every answer also says what could not be checked and why.

We do not fill in forms, we do not enter password-protected areas and we do not follow what happens after a click. We do not give opinions on design, copy or brand. This does not replace an audit or testing with people.

## Install

From your terminal:

```
claude plugin marketplace add qtorb/uxmachine-plugin
claude plugin install uxmachine@uxmachine
```

Step-by-step guide for Claude Code: https://uxmachine.app/en/agents/claude-code

The first time you use it, a UXMachine window opens so you can authorize access with your account. If you do not have one, you can create it there. Each measurement uses 1 credit from your account; measurements that cannot be made use none.

Using Claude on the web, desktop or mobile instead? Add the connector directly: https://uxmachine.app/en/agents/claude

## Privacy

https://uxmachine.app/en/privacy

## License

MIT. See LICENSE.

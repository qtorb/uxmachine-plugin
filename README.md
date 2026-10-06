# UXMachine for Claude Code

UXMachine opens your site in a real browser, at 1280×800 and 390×844 and on up to 11 pages, and returns what it observed: what, where, with which measurement, the observable state to bring it to and how to check it. When it cannot state something, it says so and explains why.

This plugin adds:
- the UXMachine connector (`https://uxmachine.app/mcp`), and
- a skill that tells your agent to measure a page before saying it is finished.

## Install

In Claude Code:

```
/plugin marketplace add qtorb/uxmachine-plugin
/plugin install uxmachine@uxmachine
```

The first time your agent uses UXMachine, a UXMachine window opens so you can authorize access with your account. If you don't have one, you can create it there. New accounts get 10 free credits.

More: https://uxmachine.app/en/agents

---
name: measure-before-done
description: Use after changing what users see on a web page, before saying the page is finished, or when asked whether an earlier observation is still there. Measures the page with UXMachine in a real browser.
---

# Measure before saying a page is finished

When you change what users see on a web page, measure it with UXMachine before you say the work is finished.

1. Call `medir` with the full address of the page. For a version running locally, call `tunel` with the server's port, run the command it returns in the background, and measure the address it prints.
2. Call `estado` with the id about every minute until the measurement has finished.
3. To check whether something changed, measure again. Pass the earlier id as `anterior` to compare with that measurement.

When you report:
- Give the report link. Say what was observed, where (page and width), and what could not be checked.
- Never say the site has "only" some problems or that it passes.
- "No longer observed" does not mean fixed. "Not comparable" is not an improvement.
- Say so if it was a local or preview version.
- If a measurement fails, report UXMachine's reason as it is.

Do not change the user's code because of a measurement unless they ask you to. Only measure sites the user owns or may review. Each measurement uses 1 credit of the user's UXMachine account.

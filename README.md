Installation & First Browser Automation

### Topics Learned

- Playwright installation
- Playwright documentation
- Launching a Chromium browser
- Running browser in headed mode
- Creating a new page
- Navigating to a website using `page.goto()`
- Using `time.sleep()` to keep the browser open

### Status

✅ Completed


## Day 2 — Playwright Locators with `get_by_role()`

### Topics Learned

- Understanding Playwright locators
- Using `get_by_role()` locator
- Locating elements by role and name
- Working with `button` role
- Working with `heading` role
- Working with `radio` role
- Working with `switch` role
- Using `click()` with role-based locators
- Using `highlight()` to verify locators

### Examples Practiced

python
page.get_by_role("button", name="Default button").click()

page.get_by_role("heading", name="Heading").highlight()

page.get_by_role("radio", name="Option").click()

page.get_by_role("switch", name="Default switch").click()


## Day 3 — Playwright Locators

### Topics Learned

- Playwright Python REPL
- Locator by Role
- Locator for Input Fields
- Locator by Text
- Locator by Alt Text
- Locator by Title
- Locating Elements with CSS Selectors
- CSS Selector Hierarchy
- CSS Selector Pseudo Classes
- XPath Locators
- XPath Functions
- Other Playwright Locators

### Practice Completed

- Located buttons, links, and input fields
- Used `get_by_role()` locator
- Used text-based locators
- Practiced CSS selector hierarchy
- Handled multiple matching elements using `.nth()`
- Practiced XPath selectors

### Status

✅ Completed


## Day 4 — Playwright Actions & User Interactions

### Topics Learned

- Mouse actions
- Actions on text input fields
- Handling radio buttons
- Handling checkboxes and switches
- Selecting dropdown options
- Handling dropdown menus
- Uploading files using `set_input_files()`
- Keyboard shortcuts using Playwright

### Status

✅ Completed

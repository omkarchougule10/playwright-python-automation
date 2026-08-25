<img width="1422" height="651" alt="image" src="https://github.com/user-attachments/assets/ca500dea-eb10-4961-a71c-286a8542b879" />## Day 1 — Playwright Installation & First Browser Automation

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

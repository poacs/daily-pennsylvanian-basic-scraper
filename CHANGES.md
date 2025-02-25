## Modified Scraper Target

I decided to target the "Sports" link on the Daily Pennsylvanian homepage. It now searches for h3 tags containing the class "standard-link" (from the HTML I inspected). Inside the found h3 element, it looks for an <a> tag to get the headline text. If either step fails, it returns an empty string.

I changed it to scrape twice per day at 3am and 3pm.
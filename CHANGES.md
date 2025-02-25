## Modified Scraper Target

I decided to target the "Sports" link on the Daily Pennsylvanian homepage. I replaced: target_element = soup.find("a", class_="frontpage-link") with target_element = soup.find("a", class_="header-section", string="Sports"). This ensures we specifically capture the link whose text reads "Sports" and whose class is "header-section". I chose this new element so I can track any changes related to sports coverage on the front page, such as how often or how prominently the sports section is highlighted.

I changed it to scrape twice per day at 3am and 3pm.
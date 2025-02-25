## Schedule Explanation

My interpetation: the cron expression `0 3 * * *` runs the scraper at 3:00am UTC every day, where:
- `0` is the minute (at minute zero)
- `3` is the hour
- `*` is for day of month, month, and day of week. here, it means "every day."

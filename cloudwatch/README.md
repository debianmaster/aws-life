```sh
aws events put-rule --schedule-expression "cron(0 8 ? * MON-FRI *)" --name start-servers-at-8am-weekdays
aws events put-rule --schedule-expression "cron(0 21 * * ? *)" --name stop-servers-at-11pm-all-days
```

# JP-KR Challenges Notice
This page provides documents and notification messages of the challenge to all participants.

## C3
- Given competition time is 6 hours.
- It's today time schedule.
  - 08:50 ~ 09:05 Reading 15m
  - 09:05 ~ 09:10 QnA 5m
  - 09:10 ~ 10:20 Competition 1h 10m
  - 10:20 ~ 10:30 Break 10m
  - 10:30 ~ 11:50 Competition 1h 20m
  - 11:50 ~ 12:40 Lunch 50m
  - 12:40 ~ 14:20 Competition 1h 40m
  - 14:20 ~ 14:30 Break 10m
  - 14:30 ~ 16:20 Competition 1h 50m
- The grow application provides the /growadmin page. This page must not be accessible from the Internet.
- Traffic will be injected starting 2 hours later.
- The scoreboard is provided on the grafana dashboard. you can open the below URL.
  - http://52.79.102.202:3000
  - The host will provide the username and password via group chat.
  - The score is an item regarding traffic processing.

## C2
- Given competition time is 6 hours
- It's today time schedule.
  - 08:40 ~ 08:55 Reading 15m
  - 08:55 ~ 09:00 QnA 5m
  - 09:00 ~ 10:20 Competition 1h 20m
  - 10:20 ~ 10:30 Break 10m
  - 10:30 ~ 11:50 Competition 1h 20m
  - 11:50 ~ 12:40 Lunch 50m
  - 12:40 ~ 14:20 Competition 1h 40m
  - 14:20 ~ 14:30 Break 10m
  - 14:30 ~ 16:10 Competition 1h 40m

## C1
- Given competition time is 5 hours.
- It's today time schedule.
  - 10:00 ~ 11:50 Competition 1h 50m
  - 11:50 ~ 12:40 Lunch 50m
  - 12:40 ~ 14:20 Competition 1h 35m
  - 14:25 ~ 14:40 Break 15m
  - 14:40 ~ 16:15 Competition 1h 35m
- All EC2 instances must be connected via SSM Session Manager. Do not use key-pair.
- Any other options can be configured refer the well-architected framework 6 pillars.
- All EC2 instances must allow all ICMP protocol from 10.0.0.0/8 of inbound rule and allow all ICMP protocol to 0.0.0.0/0 of outbound rule.

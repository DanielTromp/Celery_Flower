Flower: Real-time Celery web-monitor

This Dockerfile is based on: https://github.com/mher/flower
Added in this version is the right timezone for me ('Europe/Amsterdam').
(the right timezone is important to Celery and a known issue with some Docker images)

From: https://docs.celeryproject.org/en/latest/userguide/monitoring.html#flower-real-time-celery-web-monitor
Flower is a real-time web based monitor and administration tool for Celery. It’s under active development, but is already an essential tool. Being the recommended monitor for Celery, it obsoletes the Django-Admin monitor, celerymon and the ncurses based monitor.
Flower is pronounced like “flow”, but you can also use the botanical version if you prefer.

<H1>Flower: Real-time Celery web-monitor</H1>

docker run -p 5555:5555 -e CELERY_BROKER_URL=redis://localhost:6379 danieltromp/flower:latest<br>
(make sure you have a redis running localy or change 'localhost' in the correct IP/Hostname)

This Dockerfile is based on: https://hub.docker.com/r/mher/flower <br>
Added in this version is the right timezone for me ('Europe/Amsterdam').<br>
(the right timezone is important to Celery and a known issue with some Docker images)

From: https://docs.celeryproject.org/en/latest/userguide/monitoring.html#flower-real-time-celery-web-monitor<br>
Flower is a real-time web based monitor and administration tool for Celery. It’s under active development, but is already an essential tool. Being the recommended monitor for Celery, it obsoletes the Django-Admin monitor, celerymon and the ncurses based monitor.<br>
Flower is pronounced like “flow”, but you can also use the botanical version if you prefer.

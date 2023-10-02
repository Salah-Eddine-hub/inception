all:
	start
start:
	docker-compose up
remove:
	docker-compose -f docker-compose.yml stop
	docker-compose -f docker-compose.yml down -v
	docker system prune -af
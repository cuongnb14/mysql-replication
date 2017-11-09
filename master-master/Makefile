restart:
	docker-compose restart

clean:
	docker-compose stop && docker-compose rm && sudo rm -rf mysql-data1 mysql-data2

up:
	docker-compose up -d
re-up:
	make clean && make up
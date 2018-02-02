all: up

restart:
	docker-compose restart

clean:
	docker-compose stop && \
	docker-compose rm && \
	sudo rm -rf mysql-1/mysql-data mysql-1/mysql-logbin/mysql-* \
				mysql-2/mysql-data mysql-2/mysql-logbin/mysql-* 

up:
	docker-compose up -d
re-up:
	make clean && make up
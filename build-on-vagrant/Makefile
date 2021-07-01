TIMESTAMP:=$$(date "+%Y-%m-%d_%H-%M-%S")

create:
	vagrant up

rebuild:
	vagrant provision

test:
	@mkdir -p ./tests/
	@echo "Log output file: ./tests/test_$(TIMESTAMP).log"
	@vagrant ssh -c "cd /vagrant/receptor && make test" > ./tests/test_$(TIMESTAMP).log

clean:
	vagrant destroy -f
	rm -rf ./receptor/
	rm -rf ./test/
	rm -rf ./.vagrant/

.PHONY: test

test:
	PYTHONPATH=. py.test --verbose -s

test-infinity:
	PYTHONPATH=. ptw 

deps:
	pip3 install -r requirements.txt && \
	pip3 install -r test_requirements.txt

# to ignore use: # noqa
lint:
	flake8 solution test

DISTFILES=cron.py readme.txt

all:

dist:
	-rm pycron.tar.gz
	tar cf pycron.tar ${DISTFILES}
	gzip pycron.tar
	-rm pycron.zip
	zip -l pycron.zip ${DISTFILES}

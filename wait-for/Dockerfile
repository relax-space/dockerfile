FROM alpine
WORKDIR /bin
COPY . .
RUN chmod +x ./wait-for.sh
CMD echo "wait mysql..." && /bin/wait-for.sh test-mysql:3306 -t 36000 -- echo "wait completed"


FROM mongo-express

RUN wget https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh
RUN chmod a+x wait-for-it.sh
CMD ./wait-for-it.sh mongo:27017 -- tini -- /docker-entrypoint.sh

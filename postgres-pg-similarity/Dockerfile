ARG PG_VERSION=latest

FROM postgres:$PG_VERSION

RUN apk add --update --no-cache git build-base llvm clang
RUN git clone https://github.com/eulerto/pg_similarity.git /pg_similarity
RUN cd /pg_similarity && make && make install
COPY pg_similarity.sql /docker-entrypoint-initdb.d/pg_similarity.sql
FROM rpungello/laravel-sail:8.2

LABEL maintainer="Rob Pungello"

ARG WWWGROUP

RUN groupadd --force -g $WWWGROUP sail
RUN useradd -ms /bin/bash --no-user-group -g $WWWGROUP -u 1337 sail

EXPOSE 8000

ENTRYPOINT ["start-container"]
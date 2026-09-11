FROM ruby:4.0

WORKDIR /app

COPY . .

RUN bundle install

ENV AWS_ACCESS_KEY_ID=dummy_access_key
ENV AWS_SECRET_ACCESS_KEY=dummy_secret_key


CMD ["rake", "test"]
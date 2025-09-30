FROM ruby:3.2

WORKDIR /app
COPY Gemfile* ./
RUN bundle install

COPY . .
CMD ["rails", "server", "-b", "0.0.0.0"]

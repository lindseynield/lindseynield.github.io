## :wave: Hi, I'm Lindsey

Welcome to the source code for my website [www.lindseynield.me](https://lindseynield.me/)


### Testing Changes Locally (MacOS)
Ensure that `ruby` and `jekyll` are installed. It is recommended that `chruby` be used to manage multiple Ruby versions.
```bash
brew install ruby-install chruby
ruby-install ruby 3.3.0
chruby 3.3.0
gem install bundler jekyll
```

Install the dependencies via `bundler` and serve the project locally:
```bash
bundle install
bundle exec jekyll serve
```

Navigate to http://localhost:4000/ to view code changes. 
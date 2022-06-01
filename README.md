# README

```
rvm use 3.0.3
gem install rails -v 7.0.1
rails _7.0.1_ new rails_7 -T --database=postgresql --javascript=esbuild --css=bootstrap
Add "scripts": { "build:css": "sass ./app/assets/stylesheets/application.bootstrap.scss ./app/assets/builds/application.css --no-source-map --load-path=node_modules" } to your package.json
rails db:create
rails db:migrate
```

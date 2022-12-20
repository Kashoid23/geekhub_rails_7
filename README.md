# README

```
rvm use 3.0.3
gem install rails -v 7.0.1
rails _7.0.1_ new rails_7 -T --database=postgresql --javascript=esbuild --css=bootstrap -a propshaft
Add scripts to your package.json
"scripts": {
  "build": "esbuild app/javascript/*.* --bundle --sourcemap --outdir=app/assets/builds",
  "build:css": "sass ./app/assets/stylesheets/application.bootstrap.scss ./app/assets/builds/application.css --no-source-map --load-path=node_modules"
}
rails db:create
rails db:migrate
bin/dev
```

- [https://turbo.hotwired.dev](https://turbo.hotwired.dev)
- [https://hotwired.dev](https://hotwired.dev)
- [https://stimulus.hotwired.dev](https://stimulus.hotwired.dev)

```
rails g scaffold message body:text
```

```
rails _7.0.1_ new rails_7 -T --database=postgresql --javascript=webpack --css=tailwind
```

https://guides.rubyonrails.org/working_with_javascript_in_rails.html

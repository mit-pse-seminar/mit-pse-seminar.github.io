PSE-seminar
===========

## How to build locally
First, install jekyll by following the instructions [here](https://jekyllrb.com/docs/installation/).

Then, clone this repository:
```shell
git clone https://github.com/mit-pse-seminar/mit-pse-seminar.github.io
```

Install the dependencies
```
cd mit-pse-seminar.github.io
bundle install
```

Locally build and serve the website
```
bundle exec jekyll serve --baseurl=""
```

The website will be locally hosted at `localhost:4000`.

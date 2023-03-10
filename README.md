# Robin Altrock`s Curriculum Vitae

Online version of the CV can be found here : https://t4e-dev.github.io/

## Technologies used

- Github pages https://pages.github.com/
- Jekyll https://jekyllrb.com/
- Jekyll Theme Resume https://jekyllthemes.io/theme/resume-template

----

## Development

### Locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

*Note: You will need version `1.15.2` of bundler, as this is the only version that Heroku supports.*

1. Fork and or clone this repository locally
2. `cd modern-resume-theme`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

***Note:** You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

### Docker

If you have docker installed you can simply run `docker-compose up` to launch the site in a container, it will then be hosted at `http://localhost:4000`

### Export to pdf

The quick and dirty way :  

```zsh
wkhtmltopdf --page-width 210 --page-height 1100  http://localhost:4000 cv-robin-altrock.pdf
```

### More information and credits

Please visit : https://github.com/sproogen/modern-resume-theme

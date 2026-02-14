# The four-hour Tester

## Important

This repo is longer maintained and has been moved to Codeberg: https://codeberg.org/joeposaurus/four-hour-tester.

The site itself has moved to https://fourhourtester.smallsheds.garden/index.html

---

### Contributing an exercise

#### If you're not comfortable with git and GitHub
1. grab a copy of `templates/Exercise-template.markdown`
1. rename the file and add your content
1. send the file to fourhourtester@gmail.com

#### If you are comfortable with git and GitHub
1. fork the repository
1. grab a copy of `templates/Exercise-template.markdown`
1. rename the file, move it to `_exercises` and add your content
1. submit a pull request

### Contributing a solution to an exercise
It's basically the same as contributing an exercise, except you grab `templates/Solution-template.markdown` and it goes into the `_solutions` folder.

### Adding a blog post
Send a mail to fourhourtester@gmail.com or submit a pull request with an update to `_data/blogposts.yml`.

### Running locally
1. (first time only) `bundle install` to install Jekyll
1. edit `_config.yml` so url is pointing to local host, otherwise links in the header will point to actual site
1. `bundle exec jekyll serve`

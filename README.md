<h1 align="center">
  <br>
  <img src="teche.jpg" alt="teche" width="200"></a>
  <br>
  Tech-E Site
  <br>
  </h1>
  
 <h4 align = "center">A website for UTEP's Tech-E program under Learning Environments</h4>
 <p align = "center">
  <a href="#dependencies">Dependencies</a> |
  <a href="#setup">Setup</a> |
  <a href="#deploy">Deploy</a> |
 </p>

### Dependencies
This site is built with Ruby and uses the Gem package manager. Both need to be installed to deploy and serve the website.
1. Ruby, check by running `ruby -v`. If it is missing you can install ruby using `brew install ruby` on macOS. For windows you can download the installer linked [here](https://rubyinstaller.org/). For Ubuntu/Debian you can `apt install ruby-full`
2. Gem, checky by running `gem -v`. If it is missing you can install it by downloading the appropriate file [here](https://rubygems.org/pages/download).
3. Jekyll, you can install this with `gem install jekyll`. You might need to run the command as *sudo*.

### Setup
1. Clone this repo to your local machine with `git clone https://github.com/KevinApodaca/Tech-E.git`
2. Navigate to the directory with `cd`
3. This should not be necessary, but just in case, run the command `bundle install`.
3. Once in the directory run the following command, `bundle exec jekyll serve`
4. Verify that the `Gemfile` contains the jem for Search Engine Optimization:
```ruby
gem 'jekyll-seo-tag'
```
and that the `_config.yml` file has the following:
```yml
plugins:
  - jekyll-seo-tag
```

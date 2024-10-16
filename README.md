# Department of Energy (DOE) Office of Electricity (OE) Microgrid Research and Development Program Software Database

The MG-RAVENS project that will support the development the software database to be contained in this repository has not yet officially started. Interested parties should contact Russell Bent or David Fobes at Los Alamos National Laboratory for more information.

## Running the website locally

You must have `ruby` / `gem` installed on your machine, for example using `homebrew` (on a M1 Mac):

```sh
brew install chruby ruby-install
ruby-install 3.3.5
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.3.5" >> ~/.zshrc # run 'chruby' to see actual version
source ~/.zshrc
```

Then you need to install jekyll:

```sh
gem install jekyll bundler
```

Then you can run the website:

```sh
jekyll serve --livereload
```

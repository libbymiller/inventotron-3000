# inventotron-3000

install and use at least Ruby 2.2.0, e.g `rvm use 2.2.1`

install gems `gem install squib`

run: `ruby hackspace_cards.rb`

# Troubleshooting

```pkg-config.rb:319:in `parse_pc': .pc for libffi doesn't exist. (RuntimeError)```

then

```
brew reinstall libffi
export PKG_CONFIG_PATH=/usr/local/opt/libffi/lib/pkgconfig```

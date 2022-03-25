# DegenKingdoms WiKi for DeFi Kingdoms

A community maintained wiki for [DeFi Kingdoms][dfk] brought to you by [Degen Heroes][dh].


# Install Jekyll on your local

The following install instructions are from: [https://jekyllrb.com/](https://jekyllrb.com/).

```
gem install bundler jekyll
```

After installing jekyll, enter the working directory and start the jekyll server:

```
bundle exec jekyll serve
```

If this breaks with a reason of:

> [...] servlet.rb:3:in `require': cannot load such file -- webrick (LoadError)

then perform this additional step:

```
bundle add webrick
```

[dfk]: https://defikingdoms.com
[dh]: https://discord.gg/degenheroes

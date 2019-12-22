[![Build Status](https://travis-ci.org/Zomzog/zomzog.fr.svg?branch=master)](https://travis-ci.org/Zomzog/zomzog.fr)

Zomzog.fr
==========

This is sources for [zomzog.fr](https://zomzog.fr/).

# Requirement

1. snap install hugo --channel=extended
2. gem install asciidoctor

# Using

## With docker
docker run --rm -it   -v $(pwd):/src   -p 1313:1313   klakegg/hugo:0.61.0-asciidoctor   server -D

## With install
1. First, [install Hugo](https://gohugo.io/overview/installing/);
2. Then, clone this repository;
3. Run Hugo and select the theme of your choosing.

In other words:

<pre><code>git clone https://github.com/Zomzog/zomzog.fr.git
cd zomzog.fr
hugo server -t zomzog.fr-theme -D
</code></pre>
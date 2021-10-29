[![Build Status](https://travis-ci.org/Zomzog/zomzog.fr.svg?branch=master)](https://travis-ci.org/Zomzog/zomzog.fr)

Zomzog.fr
==========

This is sources for [zomzog.fr](https://zomzog.fr/).

# Requirement

## With docker

### Bash
docker run --rm -it   -v $(pwd):/src   -p 1313:1313   klakegg/hugo:0.83.1-asciidoctor   server -D

### Fish shell
docker run --rm -it   -v $PWD:/src   -p 1313:1313   klakegg/hugo:0.83.1-asciidoctor   server -D

## With install
1. snap install hugo --channel=extended
2. gem install asciidoctor

<pre><code>git clone https://github.com/Zomzog/zomzog.fr.git
cd zomzog.fr
hugo server -t zomzog.fr-theme -D
</code></pre>
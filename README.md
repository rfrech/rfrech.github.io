<img src="img/websiteprof.png" width="300">

## Introduction

I'm a former restaurant manager, currently participating in Cohort 11's Deep Dive Coding Java + Android bootcamp. 
My goal is to have the tools I need to develop my own apps upon graduating from the program.

## Current projects

* [TuneFull Musical Social App](https://tunefull.github.io/)

* [Battle For Midway](https://rfrech.github.io/battle-for-midway/)

### Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }}) 
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/roderick-frechette-b7a8901b5/)
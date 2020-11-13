## Introduction

I'm a former restaurant manager, currently participating in Cohort 11's Deep Dive Coding Java + Android bootcamp. 
My goal is to have the tools I need to develop my own apps upon graduating from the program.

## Current projects

* [Hello World: Java console application](https://github.com/rfrech/deep-dive-hello-world-ij)

* [Hello World: Android app](https://github.com/rfrech/android-hello-world)

### Recently updated repositories

{% assign public_repositories = site.github.public_repositories | where: 'fork', false | sort: 'updated_at' | reverse %}
{% for repo in public_repositories limit: 10 %}
* [{{ repo.name }}]({{ repo.html_url }}) 
{% endfor %}

## Links

* [LinkedIn](https://www.linkedin.com/in/roderick-frechette-b7a8901b5/)
---
title: Getting started with the Documentation Theme for Jekyll
keywords: sample homepage
sidebar: home_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the theme. The other topics in this help provide additional information and detail about working with other aspects of this theme and Jekyll.
---

## Screenshot with Link

{% include screenshot.html img="https://github.com/SiLeBAT/BfROpenLabResources/raw/master/GitHubPages/documents/foodchainlab_geocluster/1.png" %}

## Alerts

{% include note.html content="This is interesting." %}
{% include warning.html content="Pay attention." %}
{% include important.html content="This is important." %}
{% include tip.html content="Try this." %}
{% include callout.html content="This is my callout. It has a border on the left whose color you define by passing a type parameter. I typically use this style of callout when I have more information that I want to share, often spanning multiple paragraphs. " type="primary" %}

## Markdown

[Link](p2_sample3.html)

!["Logo Title Text 1"](https://github.com/thoens/documentation-template/raw/master/images/company_logo.png)

```
gem install bundler
gem install bundler
gem install bundler
```

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* Do this
* Do that

```java
public static enum Provider {
	MAPQUEST("MapQuest"), GISGRAPHY("Gisgraphy"), BKG("Bundesamt für Kartographie und Geodäsie");

	private String name;

	private Provider(String name) {
		this.name = name;
	}

	@Override
	public String toString() {
		return name;
	}
}
```

---
layout: default
title: Home
---

# {{ site.title }}

{{ site.description }}

## Download

Get the latest release of {{ site.title }}:

### Latest Release

{% if site.github.latest_release %}
**Version:** {{ site.github.latest_release.tag_name }}
**Released:** {{ site.github.latest_release.published_at | date: "%B %d, %Y" }}

[Download Latest Release]({{ site.github.latest_release.html_url }}){: .btn .btn-primary}
{% else %}
Visit our [releases page](https://github.com/{{ site.repository }}/releases) to download the latest version.
{% endif %}

## Features

- Feature 1
- Feature 2
- Feature 3

## Getting Started

1. Download the latest release above
2. Extract the files
3. Follow the installation instructions in the README

## Repository

View the source code on [GitHub](https://github.com/{{ site.repository }}).

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/{{ site.repository }}/issues).

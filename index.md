---
Author: Amrita Chatterjee
layout: template
---


# Introduction

This file is created by {{page.Author}}.

# Version History

{% for item in site.data version %}
- {{item.name}},{{item.model}}
{% endfor %}

# Overview

This is a Readme file for the DAC_learning Repo. This file includes some basic **markdown syntax** usage.

## Markdown Syntax

The following Markdown syntax are used in this file.
-  a Hash sign for Headings
-  An asterisk symbol for bold emphasis
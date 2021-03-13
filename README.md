# Lab: 26 Intro to Django

[link to PR](https://github.com/ashcaz/django-snacks/pull/1)

## Overview

The first words you see on the Django website are

_Django makes it easier to build better Web apps more quickly and with less code_.

The next quote you’ll see is

_The web framework for perfectionists with deadlines_.

In this class we’ll build out a small, but functional, multi page web site using Django.

We’ll get a feel for the “Django Way” and see the dramatic performance gains you can get with a mature, robust framework.

## Feature Tasks and Requirements

- Create web site in Django with 2 pages
  - home page
  - about page
  - create views/urls/templates as needed for home and about pages
  - use ancestor template to contain navigation elements
  - Should be built the “Django way” aka match the structure of in-class demo

## Implementation Notes

- Typical Steps to Start Django Project
  - create project
  - define app
  - add app to project
  - add views
  - add urlpatterns
  - add templates
  - add tests

## User Acceptance Tests

- Use Django’s built in testing tools
  - Test that `home` and `about` url status codes
  - Test `home` and `about` url template use, including ancestor template.

---
layout: post
title: Turning PostgreSQL 9.x Credentials Into a RCE
date: 2017-10-26
tags: research sql rce
---

This is a post from my time at Dionach. The existing tooling for obtaining RCE with PostgreSQL did not work with PostgresSQL 9.x and higher. This post details the changes that have to be made to achieve RCE in these version, and links to a script I developed to automate the process.

<https://www.dionach.com/blog/postgresql-9-x-remote-command-execution/>
# TL;WR

0️⃣ -> This is for [GraphQL/TypeScript Schema Packages for Rapid Development][1]

1️⃣ -> [Pre Workshop Survey][4]

2️⃣ -> `git clone git@github.com:xdumaine/tree-db.git && cd tree-db && ./clone.sh && cd tree-db-service && yarn && yarn start`

3️⃣ -> [Post Workshop Survey][3]

# Tree DB

The Only Tree Database app you'll ever need\*

\* if you decide to implement it and populate it with a ton of data.

## Why Trees?

I love trees, and I needed a simple concept to build an API/App around

## Purpose

This repo is part of [Xander Dumaine's TypeScript+GraphQL workshop][1] for [StrangeLoop 2022][2].

The `clone.sh` script will clone multiple repos into this directory, for working with
the example app/service/monitor to emulate how to share both GraphQL Schema and typescript types
across multiple projects developed asynchronously in parallel.

## Guide

The repos each have a general branching structure of Steps (`step-#`) to allow us to level-set our work as we go.

This means if you get stuck, or fall behind, you can stash or branch and commit your changes, then checkout the next step to get back in sync with the rest of the workshop.

I used `yarn` and `node 16.16` for developing these, and I'd recommend you use the same. If you don't, your mileage may vary, but I'll do my best to help you get going as time allows.

## Goals

Through this workshop, I'd like you to learn the following:

1. Create a GraphQL Schema with Advanced Types (Interfaces/Unions/Enums/Composite Fragments)
2. Create GraphQL requests (queries and mutations) for your schema (with best practices)
3. Create configuration to generate TypeScript definitions for your schema and queries
4. Learn how to use a versioned type library to consume your new strongly-typed (in both GraphQL and TypeScript) API schema from multiple projects/repositories

## Feedback

If you haven't yet completed the pre-workshop survey, please [do so!][4]

I'd love to hear if this helped or didn't help, please [complete this short survey][3] after the workshop

[1]: https://thestrangeloop.com/2022/graphql-slash-typescript-schema-packages-for-rapid-development.html
[2]: https://thestrangeloop.com/
[3]: https://docs.google.com/forms/d/e/1FAIpQLSdZ6_0qi5RyRVXDNDBRLJS-Cl6RUNHxf5oBoHhFE3yjycdZRw/viewform
[4]: https://forms.gle/DPixdVuciVQUquVA8

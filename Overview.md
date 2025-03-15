# Introduction

The **Star Wars API (SWAPI)** is a public API that provides data from the Star Wars universe, including information on characters, films, planets, and more. This document will help you to make an API call to retrieve various details about the Star Wars universe.

## Getting started

### Base URL

The API is available at [SWAPI] (https://swapi.dev/api/)

### Prerequisites

You can use curl or httpie to make API calls. You can install it from curl or httpie using the package manager of your choice.

### Authentication/Authorization

SWAPI is an open API that does not require Authentication/Authorization.

### Pricing

SWAPI is absolutely free to try.

###Status codes

The following are the HTTP status codes that you may encounter when using the API. 

| Status code |	Description |
| ---- | ---- | 
| 200 OK | Indicates a successful response. |
| 404 Not found	| Indicates that there are no people with the specified id. |

### Throttling limits/Rate limits

We have an API throttle that blocks IP addresses that exceed our API rate limits. The rate limit for general API requests via an IP address is 10000 requests per day.

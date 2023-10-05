## Project Description

This project demonstrates the use of a Fastify Gateway and an Express REST API, connected through a proxy server. The goal is to showcase the handling of incoming requests, their translation, and how the two services communicate.

## Introduction

In this project, we have two main components:

Fastify Gateway: This submodule serves as an entry point for incoming requests. It receives HTTP requests and forwards them to the appropriate service, translating requests if needed. The Fastify Gateway uses Fastify, a high-performance web framework.

Express REST API: This submodule is an example of an Express-based REST API service. It receives requests forwarded by the Fastify Gateway, processes them, and sends responses. If necessary, it can translate requests from one format to another.

The Fastify Gateway and the Express REST API are connected through a proxy server. The proxy server routes incoming requests to the appropriate service, demonstrating how different services can work together within a larger system.
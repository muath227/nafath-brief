Version: NAFATH-V3
Track: Networking

## Overview
A government AI assistant can help citizens find accurate information about public services through a mobile application. Building a reliable assistant requires cooperation between six IT fields. Software engineering manages the public API and ensures that updates do not break existing applications. Artificial Intelligence uses Retrieval-Augmented Generation (RAG) to provide answers based on trusted government information. Mobile development ensures secure communication between the application and its servers. Networking supports communication between devices and services using internet protocols such as IPv4 and IPv6. Cybersecurity protects the assistant against attacks that could manipulate its responses or expose sensitive information. Data management protects citizens' privacy when storing and processing chat records. Together, these fields help create a secure, accessible, and trustworthy digital service.
## Software
Semantic Versioning uses three numbers: MAJOR.MINOR.PATCH. The public API must increase its MAJOR version when a change is not backward compatible, such as removing an existing endpoint that mobile applications depend on. The MINOR version increases when new functionality is added without breaking existing clients. The PATCH version increases for backward-compatible bug fixes. Following these rules helps developers understand whether an API update could affect the government assistant's mobile application.

Resource: Semantic Versioning 2.0.0 - https://semver.org/spec/v2.0.0.html
## AI
Retrieval-Augmented Generation (RAG) combines a language model with information retrieved from external documents. Before answering a citizen's question, the assistant can search approved government documents and use the relevant information to generate its response. This helps reduce incorrect or outdated answers because the model is supported by external knowledge instead of relying only on its training. However, RAG does not guarantee accuracy, so the retrieved information must be reliable.

Resource: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks - https://arxiv.org/abs/2005.11401
## Mobile
App Transport Security (ATS) is an iOS security feature that requires secure network connections using HTTPS and appropriate TLS settings. It helps protect information exchanged between the government's mobile application and its servers. If the application attempts to connect to a plain HTTP endpoint, ATS normally blocks the connection because it is not encrypted. Developers can configure specific exceptions, but these should be avoided unless necessary because they reduce connection security.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections
## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question

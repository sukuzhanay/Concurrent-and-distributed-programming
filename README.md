# Concurrency & Socket Programming in Java

Small educational examples of a producer–consumer buffer and a TCP client/server interaction.

## Scope

The examples are separate exercises. The buffer uses semaphores for occupancy; the socket exercise uses port 704. Thread-safety, shutdown behavior and server hardening are not established by this documentation review.

## Technology / Material

Java · threads · semaphores · TCP sockets

## Repository guide

- [Buffer.java](Buffer.java)
- [Producer.java](Producer.java)
- [Consumer.java](Consumer.java)
- [Program.java](Program.java)
- [Server.java](Server.java)
- [Cliente.java](Cliente.java)

## Getting started / Reproducibility

Compile with a JDK using the source-file encoding expected by your compiler; some accented text uses legacy encoding. `Program` starts the producer–consumer exercise. Run `Server` before `Cliente` for the socket exercise; port 704 may require operating-system privileges, so adapt the local exercise configuration before use.

## Author & learning context

**Christian Vladimir Sucuzhanay Arévalo**

Data & AI Solutions Architect | AWS Data Architecture | Generative AI & Amazon Bedrock | Big Data | Former University Lecturer

[Entity Home](https://christiansucuzhanay.com/) · [Technical Portfolio](https://sukuzhanay.github.io/) · [LinkedIn](https://www.linkedin.com/in/sucuzhanay) · [AWS Builder](https://builder.aws.com/community/@sucuzhanay) · [GitHub](https://github.com/sukuzhanay)

**Build. Explain. Teach. Share.**

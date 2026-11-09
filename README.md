# choplib

**A collection of small C libraries, low-level experiments, and unfinished ideas.**

choplib is a personal collection of C projects focused on data structures, memory management, concurrency, networking, and systems programming.

The idea is simple: build things from scratch, understand how they work, experiment with different approaches, and keep the results.

Some projects become reusable libraries. Others remain prototypes, and some are abandoned when they have served their purpose.

Not everything here is finished, tested, or intended for production use.

## Repositories

| Project | Description | Status | Tests | Benchmarks |
|---|---|---|---|---|
| [dynamic-array](https://github.com/choplib/dynamic-array) | Generic dynamic array with configurable capacity growth | Functional | Yes | Yes |
| [channel](https://github.com/choplib/channel) | Bounded, blocking channel using pthreads | Incomplete | No | No |
| [http](https://github.com/choplib/http) | Non-blocking HTTP/1.1 server with routing and middleware | Experimental | No | No |
| [http-workers](https://github.com/choplib/http-workers) | Worker pool and concurrent queue prototype | In progress | No | No |
| [tcp](https://github.com/choplib/tcp) | TCP socket and connection management experiment | Discontinued | No | No |

*Test and benchmark availability refers to dedicated automated suites, not manual testing or successful compilation.*

Other repositories and experiments are available in the [repository directory](https://github.com/orgs/choplib/repositories).

## Project status

Projects are classified according to their current development state.

- **Functional:** Core functionality works and has been tested, although limitations may remain.
- **Experimental:** A working implementation exists, but correctness, completeness, or reliability is not fully established.
- **In progress:** Actively evolving implementation with incomplete functionality.
- **Incomplete:** Intended functionality has not been fully implemented.
- **Discontinued:** Development has stopped. The repository is preserved for reference.

These labels are not promises of future development or maintenance.

## Philosophy

There is no requirement for every experiment to become a polished, production-ready library.

The purpose is to explore implementation details, understand trade-offs, and gradually accumulate reusable building blocks.

A project can be useful even if it is unfinished.

The repositories are independent experiments rather than components of a single framework. They may eventually be reused together, but compatibility and integration are not guaranteed.

## About

choplib was started and is currently developed and used by **[M1ralai](https://github.com/M1ralai)**.

It's a one-person collection, not a company, a framework, or a community-driven library ecosystem.

The repositories are publicly available for anyone interested in reading, experimenting with, or reusing the code.

For more complete projects and other software engineering work, visit **[github.com/M1ralai](https://github.com/M1ralai)**.

# CPU Scheduler Simulator

A CPU scheduling simulator written in C++ that models how an operating system allocates CPU time among competing processes. The project uses workload files to evaluate scheduling behavior and includes automated testing with GoogleTest.

## Features

* CPU scheduling simulation
* Workload-driven execution
* Performance metric evaluation
* Modular C++ implementation
* Automated building with Make
* Unit testing using GoogleTest

## Technologies

* C++17
* GNU Make
* GoogleTest
* Operating Systems Concepts

## Project Structure

```text
.
├── src/            Source code files
├── include/        Header files
├── workloads/      Workload input files
├── test/           Unit tests
├── googletest/     GoogleTest framework
├── Makefile        Build configuration
└── README.md
```

## Building the Project

Compile the project using:

```bash
make
```

## Running the Scheduler

Run the scheduler with a workload file:

```bash
./scheduler workloads/workload_01.txt
```

## Running Tests

Execute all unit tests:

```bash
make test
```

The test suite validates scheduler behavior, process management, and performance calculations.

## Cleaning Build Files

Remove generated files:

```bash
make clean
```

## Learning Objectives

This project demonstrates:

* CPU scheduling algorithms
* Process management concepts
* Queue-based scheduling
* Performance analysis
* Software testing practices
* Build automation with Makefiles


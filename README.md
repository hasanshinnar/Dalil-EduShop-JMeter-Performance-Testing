# EduShop – Performance Testing with Apache JMeter

## Reference & Source Repository
This project builds upon the foundational EduShop test bed framework. For additional test scripts, API definitions, performance suites, and automation setups, refer to the source repository:
**[EduShop E-Commerce Test Project Repository](https://github.com/hasanshinnar/E-Commerce-test-project-for-API---JMeter---Automation)**

## Project Overview

This project focuses on performance testing of **EduShop**, an e-commerce application, using **Apache JMeter**.

The goal is to evaluate application performance under simulated user activity, examine response behavior, identify potential performance bottlenecks, and analyze test execution results.

The project demonstrates practical knowledge of performance testing concepts and the use of JMeter to design, execute, and analyze performance test plans.

## Objectives

- Design and execute performance test plans using Apache JMeter.
- Simulate concurrent user activity against the application.
- Evaluate response times and application behavior under load.
- Collect and analyze performance testing results.
- Document findings and observations through performance reports.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Apache JMeter | Performance and load testing |
| Docker | Application environment |
| Git & GitHub | Version control and project documentation |

## Project Structure

```text
Dalil-EduShop-JMeter-Performance-Testing/
│
├── Data/
│   └── Test data used during test execution
│
├── Report/
│   └── Performance testing reports and results
│
├── test-plans/
│   └── JMeter test plans (.jmx)
│
└── README.md
```

## Test Execution

The project uses Apache JMeter to execute performance test plans against the EduShop application.

### Prerequisites

- Java Runtime Environment (JRE) or JDK.
- Apache JMeter installed.
- EduShop application running and accessible.
- Docker environment, if running the application locally.

### Running the Test Plans

**1. Clone the repository**

```bash
git clone https://github.com/hasanshinnar/Dalil-EduShop-JMeter-Performance-Testing.git
```

**2. Navigate to the project directory**

```bash
cd Dalil-EduShop-JMeter-Performance-Testing
```

**3. Open Apache JMeter**

Launch JMeter and open the required `.jmx` test plan from the `test-plans` directory.

**4. Configure the test**

Verify the target application URL, test data, and thread group configuration before execution.

**5. Execute the test**

Run the test plan and review the collected results using JMeter's available listeners and reporting tools.

## Performance Metrics

Performance testing results can be evaluated using the following metrics:

- **Response Time:** Time required for the application to respond to a request.
- **Throughput:** Number of requests processed within a given period.
- **Error Rate:** Percentage of failed requests during execution.
- **Concurrent Users:** Number of simulated users accessing the application simultaneously.
- **Percentile Response Times:** Response time distribution across different percentiles, such as P90, P95, and P99.

## Reports & Results

Performance testing reports and supporting evidence are maintained in the `Report` directory.

These reports provide a reference for reviewing test execution outcomes and evaluating the application's observed performance.

## Project Scope

This project is part of a broader QA testing initiative around the EduShop application, extending testing activities beyond functional validation to include non-functional testing.

**Focus:** Performance Testing | Load Testing | Apache JMeter | E-commerce Applications

---
Developed as part of a C# Programming Assignment for [Dalil Information Technology](https://www.linkedin.com/company/dalil-information-technology-jo).

<img width="1128" height="191" alt="image" src="https://github.com/user-attachments/assets/0e1b05a0-3036-422a-9669-48575e4fb930" />




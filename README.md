# Performance Testing Project

## Overview
This project demonstrates performance testing using Apache JMeter. The test plan evaluates the system's performance under different load conditions, focusing on metrics like response time, throughput, and error rates.

## Test Plan Details
- **File Name**: Performance_Test_Plan.jmx
- **Tool**: Apache JMeter
- **Key Elements**:
  - Thread Groups: Define the number of virtual users and load conditions.
  - Samplers: HTTP Requests to target URLs for testing.
  - Listeners: Collect and display results for analysis.

## Setup Instructions
1. Install Apache JMeter (version 5.6 or higher).
2. Clone this repository and navigate to the project directory.
3. Open the `Performance_Test_Plan.jmx` file in JMeter.

## How to Run
1. Load the JMX file in JMeter.
2. Update test parameters (e.g., thread count, ramp-up time) if needed.
3. Execute the test plan.
4. Generate an HTML report using the following command:
   ```bash
   jmeter -g sample_results.csv -o HTML_Report/

# Performance Test Notes

Tool: Apache JMeter

Scenario:
--
API endpoint tested under simulated load.

Test configuration:
--
• 200 virtual users
• ramp-up: 5 seconds
• duration: 30 seconds

Metrics monitored:
--
• active threads
• response time
• throughput
• error rate

Observations:
--
The system handled the load without critical errors.
However response time increased when the number of active users reached peak levels.

This indicates potential bottlenecks that should be analyzed under higher traffic scenarios.

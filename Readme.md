Task 7: Netdata Monitoring
This task involved using Docker to run the Netdata real-time monitoring tool.

I ran the Netdata container using the provided Docker command.

I accessed the dashboard at http://localhost:19999 to view system metrics.


❓ What This Task is About & Why It's Useful
This task introduces you to real-time system monitoring.

What it is: Netdata is a tool that gives you a live, per-second look at the "health" of a server or computer. Think of it as a super-advanced Task Manager (on Windows) or Activity Monitor (on Mac).

Why it's used: In the real world, developers and data engineers need to know how their applications are performing.

Debugging: If a website suddenly becomes slow, tools like Netdata can instantly show you if the problem is a spike in CPU usage, if the server is running out of memory, or if the disk is too busy.

Performance Analysis: As a data analyst, you might work with systems that run big data jobs. Netdata can help you see how much resource (CPU, RAM) your job is using, helping you optimize it to run faster and cost less.

Alerting: You can set up alerts so you get a notification (like an email or Slack message) before a small problem (like low disk space) becomes a major outage.
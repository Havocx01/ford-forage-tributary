# Tributary

A project from Ford's Digital Advanced job simulation on Forage.

A simple API for recording engine temperatures. It keeps the latest 10 readings in Redis and returns the most recent temperature and the average.

- `/record` - saves a temperature reading.
- `/collect` - returns the latest temperature and average.

Built with Python, Flask, and Redis. Runs with Docker.

===============
memtime_limiter
===============

It is a simple BASH script to control memory usage and timeout a process controlling the answer from timeout command written by `PSHVED timeout script <https://github.com/pshved/timeout>`_. I have renamed the timeout command to memtime_limiter.timeout since there is already a timeout command in the system. memtime_limiter can detect if the memtime_limiter.timout command is in the same folder and if not it uses system path to execute this command.

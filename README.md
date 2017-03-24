# BenchMark
More of a convenience than an intellectual break-through
## Available constructors:
1) Measure() -- Initializes the object
## Available methods:
1) boolean isDead() - Returns true if the timer has not yet started, or has been stopped.
2) boolean isPaused() - Returns true if the timer has been paused.
3) long getMeasure() - Returns the time in milliseconds while the object is running.
4) void pause() - Pauses the timer until resume() or start() is called.
5) void resume() - Resumes the timer.
6) void start() - Starts the timer. Or if timer is already started and paused, resumes it.
7) long stop() - Stops the timer and returns the time in milliseconds.
## Exceptions
1) void pause() throws NullPointerException if object is dead/not yet started.
2) void resume() throws NullPointerException if object is dead/not yet started.
3) long stop() throws NullPointerException if object is dead/not yet started.
4) void start() throws Exception if object is already running, and not paused or stopped.

Adds an initializer for OSLog that eliminates the need to instantiate a new logger for each function. Allows you to specify file depth for subsystem.
Usage:
Logger(#function).log("message")

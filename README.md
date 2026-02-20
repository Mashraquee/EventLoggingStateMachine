# EventLoggingStateMachine
Centralized Logging: Every command or signal produces a timestamped log entry.

State Machine: Transitions between IDLE, RUNNING, MAINTENANCE, UPDATING, and ERROR.

CLI Harness: Accepts commands interactively (start_game, stop_game, signal door_open, update --package ..., etc.).

Log Viewer: Type logs to see all recorded events.

Error Handling: Unknown commands trigger transition to ERROR.

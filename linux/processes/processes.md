# Linux Processes and Services

## Process inspection
- ps: Show processes associated with the terminal
- ps aux: Display a broad list of processes
- top: Monitor processes and system resources
- pgrep: Find processes by name or pattern

## Process control
- echo $$: Print the current shell PID
- jobs: List jobs in the current shell
- &: Run a command in the background
- kill PID: Request process termination using SIGTERM
- kill -9 PID: Force termination using SIGKILL

## Services
- systemctl status SERVICE: Check service status
- systemctl list-units --type=service --state=running
- journalctl -u SERVICE: Inspect service logs

## Practice
- [ ] Run ps aux
- [ ] Explore top and exit using q
- [ ] Start sleep 300 in the background
- [ ] Find and stop your test process
- [ ] Check whether systemd is available

# Practical 6

## Topics

- Client-Server communication using Named Pipes (FIFOs)
- Multiple client communication
- POSIX signal handling
- SIGINT
- SIGTERM
- SIGUSR1

## Files

- fifo_server.c - FIFO server program
- fifo_client.c - FIFO client program
- signal_handler.c - POSIX signal handling program

## Compilation

### FIFO Server

```bash
gcc -Wall -Wextra -o fifo_server fifo_server.c
./fifo_server

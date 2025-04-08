# Lottery-Scheduling
This project consists of a lottery scheduling simulation.

Step-by-Step Algorithm
Initialize:

For each process, assign a number of lottery tickets (can be based on priority or equally distributed).

Store processes and their ticket ranges.

Main Loop (until all processes are completed):

Generate a random ticket number within the total ticket range.

Find the process that owns the winning ticket.

Allocate CPU to that process for a time slice or until completion.

If the process is completed, remove its tickets from the pool.

If not completed, keep it in the pool for the next round.
// Done

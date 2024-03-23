# Reflection
## Commit 1
The handle_connection takes a stream as an argument.Then, the buff reader is created from the Tcpstream.
Then, the line method will iterate over the lines of the stream. Then, the method map will unwrapped all the line. Then, the take_while method will take lines from the iterator as long as they're not empty. Finally, the collect method will collect the lines into a Vec<String> type.

## Commit 2
![Commit 2 screen capture](/assets/images/commit2.png)

## Commit 3
The refactor that I add is to use If else to load the page by the status response
![Commit 3 screen capture](/assets/images/commit3.png)

## Commit 4
The `sleep` one runs slower because the code itself command for the thread to sleep for 10 seconds in this snippet: `thread::sleep(Duration::from_secs(10));`

## Commit 5
The `pool` is used to increase the throughput of a program. The logic behind it is for assign a task to a thread in the pool where other threads wait for task.
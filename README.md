# Reflection
## Commit 1
The handle_connection takes a stream as an argument.Then, the buff reader is created from the Tcpstream.
Then, the line method will iterate over the lines of the stream. Then, the method map will unwrapped all the line. Then, the take_while method will take lines from the iterator as long as they're not empty. Finally, the collect method will collect the lines into a Vec<String> type.


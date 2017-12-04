## Streams And Buffers
- buffer is a temporary storage spot for a chunck of data that is being transferred from one place to another.

- The buffer is filled with data then moved along.
-transfer small chuncks of data at a time.

- A stream is a stream of data that flows over time from one place to another.  


- Online movies are buffers and streams in action.  

## Benefits of Streams and Buffers:
  - We can start consuming data even before it arrives. We don't have to gather all of the data in memory and then consume it.
  -  We can start consuming it bit by bit.

## How can we use streams and buffers in Node.js?
- We can create streams to read and write files in Node.js, which because of the way streams and buffers work can increase the performance of your application.

- This can help us when dealing with requests on our node server

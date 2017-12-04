## Streams And Buffers
- buffer is a temporary storage spot for a chunck of data that is being transferred from one place to another.

- The buffer is filled with data then moved along.
- transfer small chuncks of data at a time.

![buffer](https://scontent.fjrs2-1.fna.fbcdn.net/v/t34.0-12/24550324_10215207045671926_1297021289_n.jpg?oh=9cf23591a246e95522684d45e1ea1023&oe=5A287BBE)

*We want to get al of this data from point A to B, but intead of waiting all data to be stored in memory, we transfere a little bit at a time and we fill up the buffer, and then when the buffer is full , data can be passed on and processed

## Stream
- is a stream of data that flows over time from one place to another.  

![stream](https://scontent.fjrs2-1.fna.fbcdn.net/v/t34.0-12/24337521_10215207038591749_574930842_n.jpg?oh=11ecc1e69c23af9fc7e8a095df06b3f5&oe=5A27744B)


*We want to get al of this data from point A to B, but intead of waiting all data to be stored in memory, we transfere a little bit at a time and we fill up the buffer, and then when the buffer is full , data can be passed on and processed
- Online movies are buffers and streams in action.  

## Benefits of Streams and Buffers:
  - We can start consuming data even before it arrives. We don't have to gather all of the data in memory and then consume it.
  -  We can start consuming it bit by bit.

## How can we use streams and buffers in Node.js?
- We can create streams to read and write files in Node.js, which because of the way streams and buffers work can increase the performance of your application.

- This can help us when dealing with requests on our node server

## Types of streams

- Writable stram - allow node js to write data to a stream
- Readable stream - allow node js to read data from a stream
- Read and Write

*If we want to send the client some data, in this case it would be a writable stream becouse we'de be writing data to the stream and vice versa, if node was recieving data from somewhere like reading a file, then it would be readable stream, becouse it would be readinb data coming in the stream

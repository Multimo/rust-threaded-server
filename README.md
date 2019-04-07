# rust-threaded-server

A completed mutli threaded http server which returns html written in rust based on the final tutorial on the excellent rust book.

### Speacial features!

- uses 4 threads to handle multiple requests at the same time
- gracefully shuts down the threads
- a very basic routing system
- /sleep will mock a long task for 5 seconds

### potential improvements

- Add more documentation to ThreadPool and its public methods.
- Add tests of the library’s functionality.
- Change calls to unwrap to more robust error handling.
- Use ThreadPool to perform some task other than serving web requests.
- Find a thread pool crate on https://crates.io/ and implement a similar web server using the crate instead. Then compare its API and robustness to the thread pool we implemented.

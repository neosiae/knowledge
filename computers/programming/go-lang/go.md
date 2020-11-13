# Go lang

Go is a pass-by-value language.

## Goroutines

Goroutines are functions or methods that run concurrently with other functions or methods. We can think of goroutines as lightweight threads managed by the Go runtime. The cost of creating a goroutine is tiny.

## Channels

Channels are the pipes that connect goroutines. You can send values into channels from one goroutine and receive those values into another goroutine.

Sends and receives to a channel are blocking by default. When data is sent to a channel, the control is blocked in the send statement until some other goroutine reads from that channel. When data is read from a channel, the read is blocked until some goroutine writes data to that channel.

## Books

- [The Little Go Book](https://www.openmymind.net/The-Little-Go-Book/)
- [An Introduction to Programming in Go](http://www.golang-book.com/books/intro)

## See Also

- [https://gobyexample.com/](https://gobyexample.com/)

# Notes chapter 8

- Concurrent programming: the expression of a program as a composition of several autonomous activies.
- Go enables two styles of concurrent programming : communicating sequential processes (CSP) and shared memory multithreading.
- CSP includes passing data between independent activities (goroutines).
- Each concurrently executing activity is called a goroutine.
- Difference between threads and goroutines are essentially quantitative, not qualitative.
- f() // call f(); blocking call; wait for it to return.
- go f() // create a new goroutine that calls f(); non-blocking call; returns immediately.
- Returning from main() or exiting the program stops the goroutine.
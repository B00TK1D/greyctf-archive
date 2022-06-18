Out-of-bounds access is a very nice to exploit bug. Try to overwrite some values in memory to control the program's execution flow.

Hints:

https://www.youtube.com/watch?v=T03idxny9jE&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN&index=14

https://www.youtube.com/watch?v=8QzOC8HfOqU&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN&index=15

If your exploit doesn't work, consider setting the return address to ezflag+5.

It is due to this issue: https://ropemporium.com/guide.html#:~:text=aren%27t%20immediately%20obvious.-,The%20MOVAPS%20issue,-If%20you%27re%20segfaulting
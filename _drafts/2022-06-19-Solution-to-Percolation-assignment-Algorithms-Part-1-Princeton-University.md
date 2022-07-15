---
layout: post
title: "Solutions to Programming assignment"
subtitle: "Percolation problem optimised for backwash"
background: "/img/posts/Why-is-bitcoin-crashing-in-June-2022.jpg"
---

# Programming Assignment: Percolation - Solution

In this post, I will walk you through my java code for assignment 1 which I wrote as a requirement for course Algorithms, Part 1 on Coursera. The specifications for the assignment can be found here: https://coursera.cs.princeton.edu/algs4/assignments/percolation/specification.php

I do not suggest you to copy this code. Use this code as an example after you have tried to solve the assignment for yourself. Otherwise, you wont learn anything.

The assignment itself provides us with some API functions to implement:

public class Percolation {

    // creates n-by-n grid, with all sites initially blocked
    public Percolation(int n)

    // opens the site (row, col) if it is not open already
    public void open(int row, int col)

    // is the site (row, col) open?
    public boolean isOpen(int row, int col)

    // is the site (row, col) full?
    public boolean isFull(int row, int col)

    // returns the number of open sites
    public int numberOfOpenSites()

    // does the system percolate?
    public boolean percolates()

    // test client (optional)
    public static void main(String[] args)

}

Let's start with the constructor which is function 'public Percolation(int n)' in the code below. We can understand from the comments provided to us in the assignment text that we are to create a n-by-b grid. How do we do that?

First, let's ensure that we are only working with grad where n is positive. Throw an exception otherwise. Note that assignment specification also suggests us to handle exceptions as part of the requirement. Write following lines in the constructor:

```python
// creates n-by-n grid, with all sites initially blocked
    public Percolation(int n) {

        if (n <= 0)
            throw new IllegalArgumentException("n can be only greater than 0");
        else {
```

```python

```

```python

```

```python

```

```python

```

```python

```

```python

```

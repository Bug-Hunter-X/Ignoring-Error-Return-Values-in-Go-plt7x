# Ignoring Error Return Values in Go

This repository demonstrates a common error in Go: neglecting to handle the error returned by a function that can fail.  The `calculate` function correctly returns an error when dividing by zero, but the `main` function doesn't properly process this error, leading to unexpected behavior or a silent failure.

The `bug.go` file contains the buggy code.  The `bugSolution.go` file provides a corrected version.

**Key Takeaway:** Always check the error return value of functions that may fail.  Failure to do so can lead to subtle and difficult-to-debug problems.
# Go: Runtime Panic: Accessing Uninitialized Map

This repository demonstrates a common error in Go: accessing an uninitialized map. Attempting to access or modify a map literal before it is properly initialized leads to a runtime panic. 

The `bug.go` file shows the problematic code. The `bugSolution.go` file provides a corrected version.

This issue highlights the importance of properly initializing maps in Go before any operations are performed.
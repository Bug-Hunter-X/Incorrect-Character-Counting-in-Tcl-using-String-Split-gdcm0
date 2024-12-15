This repository contains a Tcl code example demonstrating a common mistake when counting characters in a string using the split command. The `bug.tcl` file shows the erroneous code, and `bugSolution.tcl` provides a corrected version.  The issue lies in the misuse of the `split` command with an empty delimiter, which does not produce individual characters as intended. The corrected code uses a different approach to achieve accurate character counting.
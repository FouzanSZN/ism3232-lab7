# debug_log.md
# Author: Fouzan Haider

## Bug 1
Error type: KeyError
File + line: week8_buggy.py, line 12
What the error means: Python tried to access a dictionary key that it could not find.
What I told the duck: get_total() starts total at 0, loops through each record, adds each record's amount to total, and returns the final total.
What I tried: I read the traceback from the bottom up and checked which line failed.
How I fixed it: Corrected the typo in Taylor's dictionary key from 'amout' to 'amount' so it matches the key used in get_total().

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means: Python cannot use > to compare an integer with a string.
How I fixed it: Removed the quotes around 1000 so Python compares two integers instead of an integer and a string.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records followed by True.
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used:  I asked for guidance on completing the Week 8 debugging lab and understanding the errors.
What AI explained: AI clarified the lab workflow and helped me understand the traceback terminology.
What I changed myself: I corrected the dictionary key typo, fixed the integer-versus-string comparison, added and removed the temporary debug print, and ran the tests myself.
Can I explain every fixed line? Yes

## What I learned
I learned how to read tracebacks to identify errors and find the lines causing them. I also learned the importance of matching dictionary keys correctly and comparing the right data types in Python. Print debugging and tests helped me verify that my fixes worked.
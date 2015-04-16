#Same Length Line Aggregator

Same Length Aggregator simply parses an input file, matching each text line's length against the user specified required length, using the inputted operator provided. If the result is true then that line is written to the new text file. 

Three operators are provided for, namely '=', '>', and '<'.

For example, with a length of 4 and the '=' operator selected:
aaa
bbbb
cccccc
dddd

will yield:
bbbb
dddd

Created by Craig Lotter, April 2006

*********************************

Project Details:

Coded in Visual Basic .NET using Visual Studio .NET 2006
Implements concepts such as threading and text file manipulation.
Level of Complexity: simple

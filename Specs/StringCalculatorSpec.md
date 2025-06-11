# String Calculator Specification

we will be doing these things in order, when a step is completed mark it as done by adding a checkmark in front of it.

[]  Given an empty string, the result should be 0.

[]  Given a single number, the result should be that number.

[]  Given two numbers separated by a comma, the result should be their sum.

[]  Given an unknown amount of numbers separated by commas, the result should be their sum.

[]  The delimiter can be specified using a special syntax at the beginning of the string, e.g., "//;\n1;2" should return 3.

[]  If the input contains negative numbers, an exception should be thrown with a message listing the negative numbers.

[]  If the input contains numbers larger than 1000, they should be ignored in the sum.

[]  The calculator should handle new lines as delimiters, e.g., "1\n2,3" should return 6.

[]  The calculator should handle delimiters of any length, e.g., "//[***]\n1***2***3" should return 6.

[]  The calculator should ignore whitespace around numbers, e.g., " 1 , 2 " should return 3.

[]  The calculator should handle empty delimiters, e.g., "//;\n1;;2" should return 3.

[]  The calculator should handle multiple custom delimiters, e.g., "//[;][#]\n1;2#3" should return 6.

[]  The calculator should handle mixed delimiters, e.g., "//[;][#]\n1;2#3" should return 6.

[]  The calculator should handle escaped delimiters, e.g., "//[;][#]\n1;2\\#3" should return 6.

[]  The calculator should handle escaped custom delimiters, e.g., "//[;][#]\n1;2\\#3" should return 6.

[]  The calculator should handle escaped mixed delimiters, e.g., "//[;][#]\n1;2\\#3" should return 6.

[]  The calculator should handle escaped empty delimiters, e.g., "//[;][#]\n1;;2" should return 3.

[]  The calculator should handle escaped whitespace around numbers, e.g., " 1 , 2 " should return 3.
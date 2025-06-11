# String Calculator Specification

we will be doing these things in order, when a step is completed mark it as done by adding a checkmark in front of it.

[]  Given_an_empty_string_the_result_should_be_0

[]  Given_a_single_number_the_result_should_be_that_number

[]  Given_two_numbers_separated_by_a_comma_the_result_should_be_their_sum

[]  Given_an_unknown_amount_of_numbers_separated_by_commas_the_result_should_be_their_sum

[]  The_delimiter_can_be_specified_using_a_special_syntax_at_the_beginning_of_the_string e.g. //;\n1;2 should return 3

[]  If_the_input_contains_negative_numbers_an_exception_should_be_thrown_with_a_message_listing_the_negative_numbers

[]  If_the_input_contains_numbers_larger_than_1000_they_should_be_ignored_in_the_sum

[]  The_calculator_should_handle_new_lines_as_delimiters e.g. 1\n2,3 should return 6

[]  The_calculator_should_handle_delimiters_of_any_length e.g. //[***]\n1***2***3 should return 6

[]  The_calculator_should_ignore_whitespace_around_numbers e.g. 1 , 2 should return 3

[]  The_calculator_should_handle_empty_delimiters e.g. //;\n1;;2 should return 3

[]  The_calculator_should_handle_multiple_custom_delimiters e.g. //[;][#]\n1;2#3 should return 6

[]  The_calculator_should_handle_mixed_delimiters e.g. //[;][#]\n1;2#3 should return 6

[]  The_calculator_should_handle_escaped_delimiters e.g. //[;][#]\n1;2\\#3 should return 6

[]  The_calculator_should_handle_escaped_custom_delimiters e.g. //[;][#]\n1;2\\#3 should return 6

[]  The_calculator_should_handle_escaped_mixed_delimiters e.g. //[;][#]\n1;2\\#3 should return 6

[]  The_calculator_should_handle_escaped_empty_delimiters e.g. //[;][#]\n1;;2 should return 3

[]  The_calculator_should_handle_escaped_whitespace_around_numbers e.g. 1 , 2 should return 3
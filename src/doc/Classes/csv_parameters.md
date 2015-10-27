Parameter          | Description        | Default       
-------------      | -------------  | ------------- 
assume_header      | Assume first row in file is header, use field names to construct objects | false         
header_lines      | Number of header lines in the CSV text | 0         
header      | A string containing delimited names corresponding to the fields in the file | Empty
data_types      | A string containing delimited data types corresponding to the columns in the file. The following data types are supported: string, integer, float and boolean | Empty
max_lines         | Maximum number of lines to read | Unlimited
line_delimiter|String to write between records|\n  
field_delimiter    | Field separator              | ,             
quote_char         | Quote character              | "             
quote_escape_char  | Character to escape quote character (by default the quote character is doubled)| "             
quote_style|all, minimal, none, or nonnumeric|minimal
comment_starter|Character to comment out a line, must be at column 1.|None
trim_leading      | Trim leading whitespace | false         
trim_trailing      | Trim trailing whitespace | false         
trim      | Trim both leading and trailing whitespace | false        
replace_empty_field_with_null | Replace empty field with json null value | false         

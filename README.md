# counting_lines_of_code
This script shows how to count the lines of code for ipynb format and other format

For plain text source code, the given python script counts it directly.
<br>For ipynb format, the given python script calls jupyter notebook to convert .ipynb to .py first.
<br>Then, it counts every lines, except the line that start with "In [xx]"

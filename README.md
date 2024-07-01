<h1>Theory-Of-Compilation-Syntax-Analyzer</h1>

<h2>Overview</h2>
<p>This project is part of the coursework for the Theory of Compilation class. It focuses on developing a syntax analyzer using Flex and Bison to parse a simple programming language. The analyzer recognizes the language's grammar and prints the production rule that matches each 'reduce' action.</p>

<h2>Features</h2>
<ul>
    <li><strong>Lexical Analysis</strong>: Tokenizes the input source code using Flex.</li>
    <li><strong>Syntax Analysis</strong>: Parses the tokenized input according to the defined grammar using Bison.</li>
    <li><strong>Error Handling</strong>: Provides detailed error messages with line numbers to help identify and fix issues in the source code.</li>
</ul>

<h2>Files</h2>
<ul>
    <li><strong>src/</strong>
        <ul>
            <li><code>scanner.lex</code>: Flex file for lexical analysis.</li>
            <li><code>parser.yyp</code>: Bison file for syntax analysis.</li>
            <li><code>output.hpp</code>: Header file for output functions.</li>
            <li><code>output.cpp</code>: Implementation of output functions.</li>
            <li><code>Makefile</code>: Script to automate the build process.</li>
        </ul>
    </li>
    <li><strong>tests/</strong>
        <ul>
            <li><code>hw2_test.zip</code>: Sample input and ouput files for testing.</li>
            <li><code>selfcheck-hw2</code>: script for checking the validity of the submission file</code>.</li>
        </ul>
    </li>
  <li><strong>submission/</strong>
        <ul>
            <li>zip file containing the final submission.</li>
        </ul>
    </li>
</ul>

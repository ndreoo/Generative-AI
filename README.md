# Comparing Comparing Quality of Human-written and AI-generated Code

The increase in the use of LLMs for code generation, is leading towards
a newevolution of the programmer’s role: from primary person respon
sible for the work to supervisor of the generated code. Furthermore
all static and dynamic analysis tools, but also tools like compilers, are
based on the viewpoint of human errors. With the advent of LLMs
like DeepSeek Coder and Qwen, the focus shifts to understanding what
are the defects and vulnerabilities introduced into real projects by AI
generated code. In this thesis we show a methodology that allows per
forming a static analysis of AI generated code to compare its results in
terms of quality with human code. To obtain the results, we analyzed
280518 snippets in C language extracted from real projects of human
code. For the static analysis of defects, it is right to observe that
such results depend on the language (C) and the specific tool used,
therefore in order to make the results comparable, we performed a 1:1
mapping between each checker and the Defect Type categories of the
Orthogonal Defect Classification (ODC). ODC is a standard approach
to classify software defects into Defect Type Categories. Each category
is mutually exclusive with the others, so a defect could be classified
in only one category. This approach helps programmers to better un
derstand what kind of defects the code is affected, so that a targeted
intervention could be done. For the analysis of vulnerabilities we have
identified the Common Weakness Enumerations from Mitre, while for
the complexity analysis, we have calculated existing metrics such as
Number Of Line Code (NLOC) and Cyclomatic Complexity Number
(CCN). The results obtained show that human code is syntactically
richer and more complex compared to the AI generated one, which in
turn turns out to be much more vulnerable in terms of security.

# If you would like to see the Python code, please contact me

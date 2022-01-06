# Problem Overview

The bioinformatics team have asked you to make a tool to determine the number of target sequences inside a reference genome.  When looking for a genetic match, you need to search for both the original target DNA sequence and its reverse complement from a string of characters that includes A, C, G, and T. The reverse complement of a DNA sequence is formed by reversing the characters and interchanging A and T and interchanging C and G. For example, the reverse complement of ATC is GAT. (Feel free to use Google to find more information about reverse complements.) You will build a tool that will take in target and reference sequences as input and return the number of times and where the target sequence can be found in the reference.

You are welcome to use whatever resources and tools you would like.

# Example Cases

Reference genome GATATC and target genome ATC will have 2 matches at the 0th and 3rd indices.

Reference genome ATCCT and target genome ATC will have 1 match at the 0th index.

Reference genome CATATGGGCAT and target genome CAT will have 3 matches at the 0th, 3rd, 8th indices.

Reference genome ACTACTACT and target genome ACTACT will have 2 matches at the 0th, and 3rd indices.


# Details

- The tool should have two required inputs "Reference Genome" and "Target Genome".
- To find a match, you will need to use the target genome to calculate its reverse complement.  Then, both the target and its reverse complement should be used to search for each in the reference genome.
- The tool should return the number of matches and their locations within the reference genome.
- The tool should validate that the inputs are properly formatted DNA sequences. If invalid input is provided, a user should be given a clear error message to help correct the input.
- The code should be treated like a production system with appropriate testing, readable names, and comments where appropriate.


# Additional considerations

The following are some additional issues that you should consider but are not required to write code for:

- For long reference genomes, performing this calculation could take a long time. How would you store the inputs and the outputs to cache the data in, for example, a relational database or other data store?
- Similarly, the reference genome has the potential to be incredibly long. How does that influence your choice of data store above?
- If we wanted to include this tool as part of a web application, how would that affect our implementation? What additional issues and considerations might arise?

Please ensure that you are prepared to discuss such issues before pairing.

# Deliverables

If you have been asked to pair on this project, please be ready with a development environment to work with during a 1 hour session. Please do not begin any development before then. It is not expected to have a finished working product before the session or even after. Do not spend more than 2 to 3 hours on prep time.

## For any work done (Pairing or "finished"):

Please create zip file from your project folder with all relevant code, setup files, and a ReadMe.  An example ReadMe has been attached as a template.

# Rubric

Your code will be evaluated on the following criteria with consideration for time constraints:

- Readability: variables, functions, and classes are named clearly indicating their purpose
- Correctness: the code solves the problem as described by the requirements
- Testing: appropriate tests are included to ensure that the code works correctly

In addition to the technical evaluation, during and after the pairing session you will be evaluated as follows:

- Communication: how well you can explain your implementation plan and any of the additional considerations described above
- Teamwork: how you work with others together to solve a problem
- Documentation: the documentation provided afterwards explains how to set up the project and the work you have done concisely

If you have any questions about the format or become stuck, please contact me directly at remig@pivotbio.com

# Constraints

-  For a pairing session, do not spend more than 2 to 3 hours on prep time.
-  For a "finished" system, do not spend more than 2 to 3 hours of effort. If you find that you have spent this amount and are not done, then please stop and send what you have. We will discuss what you have done during one or more interviews. 


# ReadMe example

```markdown
# Quickstart Instructions

## Installation

Include here all instructions for setting up your application, including installing system requirements for your prefered OS and language specific packages.  

## Testing

Include instructions here for how to perform tests.

# Explanation of methods

In this section, please explain the method or methods you have used here including both why and how they work in general terms.  

# TODO

Explain any problems that you encountered and possible solutions you would implement if you had time. This is also a good place to describe any UI and operational improvement you might want to make in the future.

```

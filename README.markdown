# Problem Overview

You are a lab tech in a pretend lab and have been tasked with making a tool to determine the number of alternations a one genome(the original) would have to have to be the same an another(the desired).  In this fake problem you will need use Django to build a web form which will take in two genomes and return the minimum number of additions and deletions required to turn the original into the desired genome.

You are welcome to use whatever resources and tools you like.  You are also strongly encouraged to Google for algorithms to do this and not design one yourself.

# Examples

If the original genome is "catg" and the desired genome is "cat" then it will be 0 insertions and 1 deletion.

If the original is "cataga" and the desired genome is "ataag" then it would be 1 insertion and 2 deletions.

If the original is "cataga" and the desired genome is "catagac" it would be 1 insertion and 0 deletions.

# Details

- Going to the url /genome_form should return a form with two required inputs "Original Genome" and "Desired Genome"
- A successful post to the same url should return the form filled out and return the numbers of deletions and addition in message as the top with the text "It would take X additions and Y deletions to transform the original into the desired genome".
- Both fields are required and should validate that they are properly formatted genomes meaning strings only containing C, A, T, and G. If an invalid form is posted then the user should be given clear error messages returned after the POST.
- This should be treated like a production website with all relevant code tested and commented.


# Deliverables

Please create zip file from your project folder with  all relevant code, setup files, and a ReadMe.  An example ReadMe as been attached please use it as a template for creating yours and fill out all of the sections.

# Scoring

Your work will primarily be evaluated based on the test quality, code readability, and the clarity of information in the ReadMe.  If you have any questions about the format or become stuck please contact me directly at mikela@pivotbio.com


```markdown
# Quickstart Instructions

## Installation

Include here all instructions for setting up your application including installing system requirements for your prefered OS as well as language specific packages.  

## Running the server

Include instructions here required to to start and stop the development server.

## Running tests

Include instructions here for how to run tests.

# Explination of methods

In this section please explain the method or methods you have used here including both why and how they work in general terms.  Also include an estimate of the time complexity required to determine the alterations required for an original genome of length m and desired genome of legnth n

# TODO

Explain any problems that you encountered and possible solutions you would implement if you had time.  This is also a good place to describe any UI and operational improvement you might want to make in the future.


```

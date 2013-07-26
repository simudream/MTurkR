## Access to Amazon Mechanical Turk Requester API via R

The **MTurkR** package provides access to the [Amazon Mechanical Turk](https://requester.mturk.com/) (MTurk) [Requester API](http://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/Welcome.html) via authenticated HTTP requests executed with [RCurl](http://cran.r-project.org/web/packages/RCurl/index.html) and a number of functions to translate API calls into R data structures (using the [XML package](http://cran.r-project.org/web/packages/XML/index.html)).

Read more about the package:
* [On CRAN](http://cran.r-project.org/web/packages/MTurkR/index.html)
* [On my website](http://thomasleeper.com/MTurkR/index.html)

### To install the latest development version from GitHub:

    # install.packages("devtools")
    library(devtools)
    install_github(repo="MTurkR", username = "leeper")

### Some code examples
* Examples in an introductory article: "[Crowdsourcing with R and the MTurk API](http://polmeth.wustl.edu/methodologist/tpm_v20_n2.pdf)" in *The Political Methodologist* 20(1):2-7.
* Examples from a blog post by Solomon Messing: "[Streamline Your Mechanical Turk Workflow with MTurkR](http://solomonmessing.wordpress.com/2013/06/24/streamline-your-mechanical-turk-workflow-with-mturkr/)
* Sample code to [create and manage qualifications](http://www.thomasleeper.com/MTurkR/qualification_test_example.r), with associated xml files for [QuestionForm](http://www.thomasleeper.com/MTurkR/questionform_example.xml) and [AnswerKey](http://www.thomasleeper.com/MTurkR/answerkey_example.xml)

# Introduction

This package is meant to test maven project test cases. It is assumed that, you have a separate project for testcases and not included
in the same package as source. 

# Running the watch

    grunt mvnwatch:<FOLDER_TO_WATCH>

# What just happened?

Running the watch will listen for .java file changes in the folder and whenever something is changed, it executes the changed
file alone - providing you with SUCCESS/FAILURE result.

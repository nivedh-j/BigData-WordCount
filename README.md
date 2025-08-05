# BigData-WordCount

# Overview

This project shows a simple way to run the WordCount program using the Hadoop MapReduce framework. It helps you understand how data processing works in a distributed system by counting how often each word appears in a text file. This is a good example to learn about Hadoop's MapReduce approach.

The WordCount program is a common example that explains how the MapReduce model functions.
It takes a big text file and splits it into smaller parts. In the Map step, each part is checked, and every word is listed with a count of one. Then, in the Reduce step, these counts are added together to find out how many times each word appears overall. This simple program shows how data can be handled at the same time across many computers using key-value pairs.

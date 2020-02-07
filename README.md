# No-Sql_LAB
This lab consists of Map Reduce programs performed on  single node cluster Hadoop.

## Question-1 : Finding maximum temperature 
This program returns yearly maximum temperature from the given input data file which consists weather of last few years.

```
Input file : Question1_input.txt
Output file : Question1_output.txt
Source code : maxTemperature.java
```

## Question-2 : Finding number of times .gif, .jpg and other image file that have been accessed by clients
This program returns the number of times GIF, JPG, and other image files that have been accessed by clients. It uses web access log file produced by a web server as an input.

```
Input file : Input_web_access_log.txt
Output file : Question2_output.txt
Source code : imgCounter.java
```

## Question-3 : Finding total number of requests and total download size 
This program returns monthly summary of total number of requests and total download size which uses the same input file as question-2.

```
Input file : Input_web_access_log.txt
Output file : Question3_output.txt
Source code : dataDownload.java
```

## Question-4 : Finding URL with 404 http response
This program lists Timestamp, URL for which http response status has been 404. 

```
Input file : Input_web_access_log.txt
Output file : Question4_output.txt
Source code : error404.java
```

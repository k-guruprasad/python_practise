#usr/bin/python
# python_practise
#I m learning python to handle bioinformatic applications
#as part of it I m trying to learn making versions of a file
#this is my basic python file
'''programme to get file names given as input arguments on command line'''
import sys
file_names=sys.argv[1:]
print (len(file_names))
'''for x in file_names:
	print ('file name is',x)
	print ("output file is"+x[len(x)-5:])'''

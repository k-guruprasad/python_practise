# python_practise
#programme to get file names given as input arguments on command line'''

#usr/bin/python
import sys
file_names=sys.argv[1:]
print (len(file_names))
for x in file_names:
	print ('file name is',x)
	print ("output file is"+x[len(x)-5:])

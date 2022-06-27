# module
Assignments

# problem 1
import sys
for line in sys.stdin:
    data = line.strip().split("\t")
if len(data) == 6:
    date, time, store, item, cost, payment = data
    print ("{0}\t{1}".format(item, cost))
    
# problem 2
input datetime
d = timedelta(seconds = -60, days = 365*3)
now = datetime.datetime.now()
print(now-d)

# problem 3   
# importing timedelta from datetime
from datetime import timedelta 
# timedelta object representing 100 days, 10 hours and 13 minutes.
obj = timedelta(days=100, hours=10, minutes=13) 
# printing timedelta object data in given format 
print(obj.days, obj.seconds, obj.microseconds) 

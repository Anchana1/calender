# calender
-----------------python----------------------------
import calendar
month, day, year = list(map(int,input().split()))
x = calendar.weekday(year, month, day)
print((calendar.day_name[x]).upper())

output
08 05 2015

WEDNESDAY

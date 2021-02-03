# codingbat.com-prob-alarm_clock
def alarm_clock(day, vacation):
  Sun=0
  Mon=1
  Tue=2
  Wed=3
  Thu=4
  Fri=5
  Sat=6
  
  if not vacation:
    if day==Sun or day==Sat:
      return "10:00"
    else:
      return "7:00"
  else:
   
    if day==Sun or day==Sat:
      return "off" 
    else:
      return "10:00"
  
    

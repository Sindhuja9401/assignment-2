# assignment-2
import random
while(True):
t=random.randint(10,99)
h=random.randint(10,99)
if(t&gt;30 and h&lt;40):
print(&quot;High temperature and values of Temperature &amp; Humidity is:&quot;,t,h,&quot;Alarm
is on&quot;)
elif(t&lt;30 and h&gt;40):
print(&quot;Low temperature and values of Temperature &amp; Humidity : &quot;,t,h,&quot;Alarm is off")

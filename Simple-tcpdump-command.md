
#### Simple tcpdump Command

1.  <b>-i eth0</b>: <i>Capture from interface eth0</i><br>





<pre>
root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0</b>
</pre>

<b>-n</b>           : do not resolve DNS<br>
<b>-X</b>           : display ASCII ( Can also use -A)<br>
<b>-s len</b>       : Capture len Length;0 means all data<br>
<b>-c count</b>     : caputer count packets only<br>
<b>icmp</b>         : capture only ICMP Packet<br>

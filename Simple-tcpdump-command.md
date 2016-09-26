
#### Simple tcpdump Command

1.  <b>-i eth0</b>: <i>Capture from interface eth0</i><br>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0</b>
  </pre>


  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-46-22.png)
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-50-08.png)




<b>-n</b>           : do not resolve DNS<br>
<b>-X</b>           : display ASCII ( Can also use -A)<br>
<b>-s len</b>       : Capture len Length;0 means all data<br>
<b>-c count</b>     : caputer count packets only<br>
<b>icmp</b>         : capture only ICMP Packet<br>

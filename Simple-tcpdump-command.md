
#### Simple tcpdump Command

1.  <b>-i eth0</b>: <i>Capture from interface eth0</i><br>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0</b>
  </pre>


  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-46-22.png)
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-50-08.png)

 [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-i) 
 
 
2.  <b>-n</b>: <i>do not resolve DNS</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -n</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-28-29.png)
  
  [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-n) 



3.  <b>-X</b>: <i>display ASCII ( Can also use -A)</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -X</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-31-30.png)

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -X -A</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-34-20.png)

<b>-s len</b>       : Capture len Length;0 means all data<br>

5.  <b>-c count</b>: <i>caputer count packets only</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -c 10</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-49-34.png)

6.  <b>icmp</b>: <i>capture only ICMP Packet</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump icmp</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-55-12.png)

7.  <b>tcpdump -i en1 -nX -s0 -c2 icmp</b>

<pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i en1 -nX -s0 -c2 icmp</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-07-29.png)
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-07-42.png)

7.  <b>tcpdump -i wlp3s0 -nX host 192.168.1.1 : </b>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0 -nX host 192.168.1.1</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-54-53.png)

 

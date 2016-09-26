
#### Simple tcpdump Command

1.  <b>-i eth0</b>: <i>Capture from interface eth0</i><br>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0</b>
  </pre>


  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-46-22.png)
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2015-50-08.png)

 <b>tcpdump -i wlp3s0</b> [[Outputfile ] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-i) 
 
 
2.  <b>-n</b>: <i>do not resolve DNS</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -n</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-28-29.png)
  
  <b>tcpdump -n</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-n) 



3.  <b>-X</b>: <i>display ASCII ( Can also use -A)</i><br>
  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -X</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-31-30.png)

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -X -A</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-34-20.png)
  <b>tcpdump -X -A</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-X-A) 


4.  <b>-c count</b>: <i>caputer count packets only</i><br>
    <pre>
    root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -c 10</b>
    </pre>
    ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-49-34.png)
    <b>tcpdump -c 10</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-c) 

5.  <b>icmp</b>: <i>capture only ICMP Packet</i><br>
    <pre>
    root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump icmp</b>
    </pre>
    ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2020-55-12.png)
    <b>tcpdump icmp</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfile-c) 

6.  <b>tcpdump -i en1 -nX -s0 -c2 icmp</b>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0 -nX -s0 -c2 icmp</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-07-29.png)
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-07-42.png)
  <b>tcpdump -i wlp3s0 -nX -s0 -c2 icmp</b> [[Outputfile] (https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfileen1) 


7. <b>tcpdump -i wlp3s0 -nX host 192.168.1.1 : </b>

  <pre>
  root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -i wlp3s0 -nX host 192.168.1.1</b>
  </pre>
  ![alt tag](https://github.com/Telmat2015/TCPdump/blob/master/image/Screenshot%20from%202016-09-26%2021-54-53.png)
  <b>tcpdump -i wlp3s0 -nX host 192.168.1.1</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfilehost) 

 8. <b>Capture HTTP traffice (port 80) into file </b>
    <pre>
    root@bertopeng17-ThinkPad-T520:/home/bertopeng17# <b>tcpdump -s 1514 port 80 -w capture_file.cpp</b>
    </pre>
  <b>tcpdump -s 1514 port 80 -w capture_file.cpp</b> [[Outputfile] ](https://github.com/Telmat2015/TCPdump/blob/master/outputfile/outputfileport80) 

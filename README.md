# round-roblin-algorithm

# Round-robin-algorithm

-> ABSTRACT:
Scheduling is the process of allocating processes to the CPU in order to optimize some objective function. There are many algorithms used to schedule processes. The Round Robin (RR) CPU scheduling algorithm is one of these algorithms which is effective in time sharing and real time operating systems. It gives reasonable response time. In Round-robin scheduling, each ready task runs turn by turn only in a cyclic queue for a limited time slice. This algorithm also offers starvation free execution of processes.


1.INTRODUCTION:
Round Robin scheduling algorithm is one of the most popular scheduling algorithm which can actually be implemented in most of the operating systems.This is the preemptive version of first come first serve scheduling. The Algorithm focuses on Time Sharing. In this algorithm, every process gets executed in a cyclic way. A certain time slice is defined in the system which is called time quantum. Each process present in the ready queue is assigned the CPU for that time quantum, if the execution of the process is completed during that time then the process will terminate else the process will go back to the ready queue and waits for the next turn to complete the execution.


2.PROBLEM STATEMENT:
Taylor is a Linux expert who wants to have an online system where she can handle student queries. Since there can be multiple requests at any time she wishes to dedicate a fixed amount of time to every request so that everyone gets a fair share of her time. She will log into the system from 10am to 12am only. She wants to have separate requests queues for students and faculty. Implement a strategy for the same. The summary at the end of the session should include the total time she spent on handling queries and average query time. The given problem is scheduling problem. The problem can be solved by Round Robin algorithm


3.DESIGN:

3.1. METHODOLOGY:


<img width="612" alt="Screenshot 2023-09-13 at 9 51 07 PM" src="https://github.com/keerthanamg/round-roblin-algorithm/assets/88154987/7d1f5924-1351-4d7f-88f6-30dfbf539645">



4.OUTPUT SCREENSHOTS:

<img width="613" alt="Screenshot 2023-09-13 at 9 53 42 PM" src="https://github.com/keerthanamg/round-roblin-algorithm/assets/88154987/79d3fedf-648b-4df3-a91b-5693eb7bbe1d">


5.CONCLUSION:

● The name of this algorithm comes from the round-robin principle, where every person gets an equal share of something turn by turn.


● Every process gets executed in a cyclic way and the processing is done in FIFO order.


● The execution of the Round Robin scheduling algorithm mainly depends on the value of the time quantum.


● As the time quantum value decreases

   ○ The response time decreases.
   
   ○ And, The number of context switches increases.

   
● As the time quantum value increases

   ○ The response time increases.
   
   ○ And, The number of context switches decreases.

   
● We can conclude that a good scheduling algorithm for a real-time and time-sharingsystem must possess the following characteristics:

   ○ Minimum context switches.
   
   ○ Maximum CPU utilization.


6.REFERENCES:
[1] Abdulrahim A., Abdullahi S. E. and Sahalu J. B. (2014) A new improved round robin (NIRR) CPU scheduling algorithm International Journal of Computer Applications 90(4).

[2] Singh P., Singh V. and Pandey A. (2014) Analysis and comparison of CPU scheduling algorithms International Journal of Emerging Technology and Advanced Engineering 4(1) 91-95.

[3] Joshi R. and Tyagi S. B. (2015) Smart optimized round robin (SORR) CPU scheduling algorithm International Journal of Advanced Research in Computer Science and Software Engineering 5(7) 568-574

[4] Rajput I. S., and Gupta D. (2012) A priority based round robin CPU scheduling algorithm for real-time systems International Journal of Innovations in Engineering and Technology 1(3) 1-11.

[5] Singh A., Goyal P. and Batra S. (2010) An optimized round robin scheduling algorithm for CPU scheduling International Journal on Computer Science and Engineering 2(07) 2383-2385.   

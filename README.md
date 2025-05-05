# 346-simulating-scheduler-algorithms-solved
**TO GET THIS SOLUTION VISIT:** [346 Simulating scheduler algorithms Solved](https://www.ankitcodinghub.com/product/346-simulating-scheduler-algorithms-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101824&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;346 Simulating scheduler algorithms Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
This programming assignment involves implementing several different process scheduling

algorithms. The scheduler will be assigned a predefined set of tasks and will schedule the tasks

based on the selected scheduling algorithm. Each task is assigned a priority and CPU burst. The

following scheduling algorithms will be implemented:

<ul>
<li>First-come, first-served (FCFS), which schedules tasks in the order in which they</li>
</ul>
request the CPU.

<ul>
<li>Shortest-job-first (SJF), which schedules tasks in order of the length of the tasks’ next</li>
</ul>
CPU burst.

<ul>
<li>Priority scheduling, which schedules tasks based on priority.</li>
<li>Round-robin (RR) scheduling, where each task is run for a time quantum (or for the</li>
</ul>
remainder of its CPU burst).

<ul>
<li>Fair share scheduling, which schedules tasks based on their user and assigns each user</li>
</ul>
the same time quantum for their tasks.

Priorities range from 1 to 10, where a higher numeric value indicates a higher relative priority.

For round-robin scheduling, the length of a time quantum is 10 milliseconds.

<strong>Calculate the average turnaround time, and waiting time for each of the scheduling</strong>

<strong>algorithms.</strong>

<strong>Fair share scheduling description</strong>

The -share scheduling policy works as follow:

Several users may exist in the system and each user may own several processes.

In each scheduling cycle the scheduler distributes a predefined time quantum of CPU between different

users and processes.

At any scheduling cycle the scheduler distributes the time quantum equally between different users that

have at least one process ready for execution.

Furthermore, the scheduler distributes each user’s time share equally between processes that belong to

that user. when calculating the time to allocate , make sure to handle floating numbers.

The order which the processes will be scheduled in one cycle is not important, i.e. there is no priority on

users and processes.

For this scheduler, the second column of the input represents the user id instead of the priority.

<strong>&nbsp;</strong>

<strong>Input</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>The schedule of tasks has the form [task name] [priority or user_id] [CPU burst], with the</strong>

<strong>following example format:</strong>

<strong>T1, 4, 20</strong>

<strong>T2, 2, 25</strong>

<strong>T3, 3, 25</strong>

<strong>T4, 3, 15</strong>

<strong>T5, 10, 10</strong>

Thus, task T1 has priority 4 and a CPU burst of 20 milliseconds, and so forth. It is assumed that all tasks arrive at the same time, so your scheduler algorithms do not have to support higher-

Priority with RR Scheduling priority processes preempting processes with lower priorities. In addition, tasks do not have to be placed into a queue or list in any particular order. Example: Assume that at the beginning of a scheduling cycle, users A, B and C exist in the system. User A owns processes P1 and P2 ready for execution. User B owns process P3 ready for execution. User C does not have any ready process. Scheduler should distribute this cycle time quantum 50% to user A and 50% to user B. Therefore, P1 and P2 should receive 25% of quantum usage each, while P3 will receive 50% of quantum. This means that if fair-share scheduler has a quantum equal to 4 seconds. Then in this scheduling cycle P1 and P2 receives 1 second each, while P3 receives 2 seconds of CPU usage.

Output

The output of the program should have the following format.

[Scheduler name]

Will run name: [Task name]

Tid: [Task id]

Priority: [Task priority]

Burst: [Time that the task will run]

Average times: waiting [X], turnaround: [Y]

If the task finishes, print Task [Taskname] finished.

At the end of all tasks print the average waiting time, average turnaround time and response

time.

Example

Priority with RR scheduling

<strong>Will run Name: T8</strong>

<strong>Tid: 7</strong>

<strong>Priority: 10</strong>

<strong>Burst: 25</strong>

<strong>Task T8 finished.</strong>

<strong>Will run Name: T4</strong>

<strong>Tid: 3</strong>

<strong>Priority: 5</strong>

<strong>Burst: 15</strong>

<strong>Will run Name: T5</strong>

<strong>Tid: 4</strong>

<strong>Priority: 5</strong>

<strong>Burst: 20</strong>

<strong>Will run Name: T4</strong>

<strong>Tid: 3</strong>

<strong>Priority: 5</strong>

<strong>Burst: 5</strong>

<strong>Task T4 finished.</strong>

<strong>Average times: waiting [X], turnaround: [Y]</strong>

<strong>Implementation</strong>

A starting point for this project is available at

https://github.com/greggagne/osc10e/tree/master/ch5/project for both Java and C.

The Driver reads in the schedule of tasks, inserts each task into a linked list, and

invokes the process scheduler by calling the schedule() function. The schedule()

function executes each task according to the specified scheduling algorithm. Tasks selected

for execution on the CPU are determined by the pickNextTask() function and are executed by

invoking the run() function defined in CPU.

<strong>The program runs as follows</strong>

<strong>Java: java Driver fcfs schedule.txt</strong>

<strong>C: make fcfs and then ./fcfs schedule.txt</strong>

Refer to the README file for more details.

You don’t need to implement the Priority with RoundRobin scheduler, instead implement the

FairShare scheduling algorithm.

<strong>Hints:</strong>

<ul>
<li>Familiarize yourself with the starting code before starting the assignment. Read the</li>
</ul>
documentation and understand the code that is already implemented.

<ul>
<li>Implement the FCFS algorithm first. Compile and run the program with the different</li>
</ul>
inputs. When it works, start the implementation of other algorithms. One idea for work

division is: All members discuss the implementation strategy (i.e. data structures to use,

what are major considerations, etc.). Then each member can implement one algorithm,

assigning another member to revise the code and test it. All members participate in the

implementation of the fair share scheduler.

<ul>
<li>Test with the input files given in the starting code.</li>
</ul>
<strong>Deliverables</strong>

You must submit the following:

<ul>
<li>A zip file of your source code for your project</li>
<li>A report (between 2 and 4 pages) detailing:</li>
</ul>
o A comparison of the scheduling algorithms considering your implementation,

their advantages and drawbacks and the average waiting and turnaround time.

You will demonstrate your work to the TA during lab sessions. <strong>Your code should run with new</strong>

<strong>input that follows the same format</strong>, regardless of the number of tasks or users.

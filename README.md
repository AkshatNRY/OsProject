# OsProject

ABSTRACT 

The Teaching Assistant has to provide assistance to the under graduate students during office hours with their programming difficulties. The TA office is just a single room with a table and chair. It is not big enough to even accommodate two students at a time. While the TA is busy assisting a student inside office, the students were allowed to wait in the waiting area outside the office which accommodates three chairs. If a chair is empty, the student may occupy it and wait for his/her turn. However, if none of the chair is empty the student decides to come back later. Each time, after assisting a student, TA checks with the students in the waiting area and calls them inside one by one to assist. TA will take a nap if he/she is left with no student in the waiting area. If in case a student arrives when TA is taking a nap, the student may wake up the TA asking for assistance

This project is related to Process Synchronization concept in operating systems

We have captured two events for which two semaphores are used. One event is, TA was napping and waking her up when the student had arrived. Second event is, Signalling the student who is waiting outside when TA becomes free. While the TA assists a student, other students are blocked and when the TA is done with assisting a student, TA will give preference to the student who is waiting for maximum time amongst all to assist next. If in case there were too many students to assist and the chairs in the waiting area were occupied, the students in the waiting area will be asked to start programming on their own till the TA becomes free. On the other hand, TA will take a nap when there are no students to assist


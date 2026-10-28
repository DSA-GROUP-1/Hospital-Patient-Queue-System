# Hospital-Patient-Queue-System


Project Title: Hospital Patient Queue System Using FIFO Queue and Max-Heap 
Its presented by the Group 1

HOSPITAL PATIENT QUEUE SYSTEM 
The Hospital Patient Queue System is a C++ program that allows users including Patients, Hospital Staff/Admins, and Medical Personnel to participate in a centralized hospital queue management process. Patients can register or log in, input their personal and medical information, select their visit type (standard or emergency), and view their current queue status along with their estimated wait time.
Patients visiting for routine check-ups are assigned to a Standard Patients Queue, which operates under a FIFO (First-In, First-Out) order—serving individuals on a first-come, first-served basis. Patients requiring critical care are routed to an Emergency Patients Queue, powered by a Max-Heap (Priority Queue). In the Max-Heap, each emergency case is assigned a severity level rating from 1 to 10, ensuring that the patient with the highest severity score is automatically positioned at the top to be served first.

The system features a Core Logic and User Interface that handles patient registration, dynamically routes patients to the appropriate queue structure based on urgency, and displays real-time queue statuses and priority levels. Hospital Staff and Admins can manage patient records, monitor both FIFO and Max-Heap queues, update patient statuses, and generate performance reports or statistics. Meanwhile, Medical Personnel can view the patient queue, call the next patient, update treatment statuses, and access comprehensive patient histories.
Project Plot The system begins when a user opens the Hospital Patient Queue System and chooses to register or log in as a Patient, Admin, or Medical Personnel. Upon successfully entering the system, the main dashboard displays user details and active queue options.

If a patient selects a standard visit, the system places them into the FIFO Queue and generates an estimated wait time. If an emergency visit is selected, the system prompts for a severity score (1–10) and inserts the record into the Max-Heap Priority Queue. The system checks whether incoming emergency cases exceed the severity level of existing queue entries; if higher, the Max-Heap instantly re-orders the queue so the critical case is handled next.
Medical Personnel can view the consolidated Patient Service output, call the next patient according to priority/order, update treatment statuses, and review patient medical histories. Throughout the process, the AVL/Heap data structures maintain balanced, operations, optimizing hospital efficiency and significantly reducing patient waiting times.

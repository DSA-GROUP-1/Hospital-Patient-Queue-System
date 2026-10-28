# Hospital-Patient-Queue-System


Project Title: Hospital Patient Queue System Using FIFO Queue and Max-Heap (Priority Queue)
Its presented by the Group 1

HOSPITAL PATIENT QUEUE SYSTEM  The Hospital Patient Queue System is a C++ program that allows users including Patients/Users, Hospital Staff/Admin, and Medical Personnel to participate in a centralized hospital queue management process. Patients can register or log in, input their personal and medical information, select their visit type (standard or emergency), and view their real-time queue status alongside their estimated wait time.

Patients visiting for non-emergency cases are routed to the Standard Patients Queue, which utilizes a FIFO (First-In, First-Out) data structure serving patients strictly in a first-come, first-served order. Patients requiring urgent medical attention are routed to the Emergency Patients Queue, powered by a Priority Queue (Max-Heap) data structure. In the Max-Heap, patients are categorized by a severity level rating from 1 to 10, ensuring that the patient with the highest severity score is dynamically placed at the top to be served first.

The system features a Core Logic & User Interface module that handles patient registration, routes patients to the correct queue data structure, and displays active queue statuses and priority levels. Hospital Staff / Admin can manage patient records, monitor both FIFO and Max-Heap queues, update patient status, and view generated reports and statistics. Meanwhile, Medical Personnel can view the patient queue, call the next patient, update treatment status, and access patient history.

Project Plot The system begins when a user opens the Hospital Patient Queue System and chooses to register or log in as a Patient/User, Hospital Staff/Admin, or Medical Personnel. Upon entering the system, the main interface presents role-based options and active queue views.

When a patient inputs their information and selects a standard visit, the system enqueues them into the FIFO queue and calculates their wait time. If an emergency visit is selected, the system prompts for a severity score (1–10) and inserts the patient into the Max-Heap Priority Queue. The Max-Heap automatically balances itself, prioritizing higher severity scores over lower ones regardless of arrival time.

Medical Personnel can access the Patient Service output module, which identifies the next patient to be called, updates the overall queue status, and delivers timely medical intervention to reduce overall patient waiting time. Throughout the process, the combination of the FIFO Queue and Max-Heap helps manage patient records and urgency levels efficiently, making the system organized, responsive, and easier to monitor.

Main Objectives

1. To develop a C++ hospital queue system with user registration, login, and role-based access for patients, staff, and medical personnel. 
2. To allow patients to input personal/medical information and select between standard or emergency visit types. 
3. To implement a Standard Patients Queue using a FIFO data structure to manage non-emergency cases fairly on a first-come, first-served basis. 
4. To implement an Emergency Patients Queue using a Max-Heap Priority Queue based on severity levels (1–10) to serve the highest severity first. 
5. To enable hospital staff and medical personnel to manage records, monitor queues, call the next patient, and update treatment statuses. 
6. To provide an efficient and user-friendly system interface that displays real-time queue statuses and reduces patient waiting times. 
Expected Output The finished program should allow users to register and log in based on their roles, input patient data, route patients to either the FIFO standard queue or Max-Heap emergency queue, track real-time statuses, and display updated patient service details. It will demonstrate how a FIFO queue and a Max-Heap data structure can be applied to a practical hospital management system while maintaining efficient data organization, fair queuing, and prompt emergency response.

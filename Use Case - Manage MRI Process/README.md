# Use Case: Manage MRI Process in a Hospital

<p align=center>
<img src="https://github.com/jpDiogo/IUI_2024_Shareable/assets/62766163/d0534d56-d8a7-4e9f-89ff-12f876339d94" width=50% height=50%>
</p>



`Actors`:
- <ins>Doctor</ins>: A medical professional who prescribes MRI scans for patients.
- <ins>Patient</ins>: An individual undergoing an MRI scan.
- <ins>Assistant</ins>: Manage the appointments and schedules for MRI exams.
- <ins>Radiology Technician</ins>: The healthcare professional responsible for operating the MRI machines.

</br>

`Process Description`:
1. Prescribing an MRI Scan:
    1. The doctor initiates a request to prescribe an MRI scan for a patient.
    2. The system validates the request, including patient details and medical justifications.
    3. If valid, the system records the MRI prescription.
2. Scheduling an MRI Appointment:
    1. Hospital staff uses the system to check MRI availability, schedule appointments, and notify patients.
3. Performing an MRI Scan:
    1. Radiology Technician logs into the system to view scheduled MRI appointments.
    2. The technician performs the MRI scan and records relevant details, such as scan duration, machine used, and any issues encountered.
4. Accessing MRI Results:
    1.  the results are processed and stored in the system after the MRI scan.
    2. The doctor reviews the MRI results and adds comments or recommendations.
    3. The patient is notified of the availability of their MRI results through the system.

</br>

`Identified opportunities`:

The integration of AI into medical justification validation (*1.2*), radiology image analysis (*4.1*), and result reporting (*4.2*) in MRI processes is driven by the pursuit of enhanced healthcare. 

</br>

`Selected use case`:

Automated Detection of Anomalies: Machine learning models, particularly convolutional neural networks (CNNs), can be trained to detect specific anomalies or structures within MRI images. For example, they can identify tumors, lesions, or other abnormalities.

`System’s First version`:

Doctors initiate image analysis within the MRI process management system by activating MRI scans with the integrated AI module. Users are kept informed of the processing status as the AI analysis progresses. Upon completion, the system displays MRI images with highlighted tumors or abnormalities. Doctors meticulously review AI findings, zooming in, and adding comments or annotations.

</br>

`System’s Final version`:

In the final version of the MRI process management system, doctors initiate image analysis by activating MRI scans within the integrated AI module. As the AI analysis progresses, users are kept informed of the processing status and benefit from real-time insights into tumor or abnormality detection. The system offers a dynamic display of MRI images with precisely highlighted tumors, lesions, or other anomalies, utilizing color-coded overlays and outlining regions of interest. Using AI-generated reports, delve deeper into the findings, accessing automated measurements, 3D reconstructions, and predictive analytics to gauge lesion growth. The user interface empowers doctors to interact with highlighted regions, zooming in for microscopic scrutiny or comparing findings across multiple MRI scans. The system's integration of these features enhances diagnostic precision and efficiency and contributes significantly to personalized medicine and data-driven patient care.

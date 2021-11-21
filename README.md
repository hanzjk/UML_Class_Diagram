# UML Class Diagram for Hospital Management System

Ward is a division of a hospital or a suite of rooms shared by patients who need a
similar kind of care. In a hospital, there are several wards, each of which may be
empty or have on it one or more patients. Each ward has a unique name. Wards are
also differentiated by gender of its patients, i.e., male wards and female wards. A
ward can only have patients of a particular gender admitted to it. Every ward has a
fixed capacity, which is the maximum number of patients that can be on it at one
time (i.e., the capacity is the 50). Different wards may have different capacities.

The doctors in the hospital are organized into teams. Each team has a unique name
or code (e.g., Orthopedics or Pediatrics) and is headed by a consultant doctor. The
consultant doctor is the senior doctor who has completed all of his or her specialist
training, residency, and practices medicine in a clinic or hospital, in the speciality
learned during residency. She or he can supervise medical students.

The rest of the team are all junior doctors. Each doctor could be a member of no
more than one team. A Patient is treated by one doctor. The entire team is also
responsible for each patient treated by any doctor on the team. However, the leading
doctor of the team is ultimately responsible for each patient.

Each patient has a patient record, which is provided when the patient is admitted.
The patient record has the patient id and details of the patient. Doctors can check
patient records whenever necessary. There are nurses in the ward. Each ward can
have up to twenty nurses. Nurses can update the patient record. The patient record
is discarded when a patient gets discharged from the hospital.

<p align="center">
  <img  width=700  height=500 src="https://user-images.githubusercontent.com/65526190/142779822-f79edc50-5fe9-4d9e-92c1-cbbe2e867df9.png">
</p>

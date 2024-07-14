# Anomaly Detection For Electrical Systems


Anomaly detection with Industrial PC-based energy measurement framework
The technical basis is a BECKHOFF Industrial PC running a TwinCAT 3 SoftPLC and using some measurement I/O modules that are able to deliver high-frequency measurements. Voltages and currents shall be measured from several measurement objects, such as different machines, electrical servo drives or other electrical consumers, preferably non-linear consumers. From these measurements, the consumed energy shall be calculated in real-time.
As a second step, using the measurements, the TwinCAT Analytics library shall be applied to extract or recognize particular features/patterns/characteristics that can easily be transmitted to a remote surveillance application.
In a further step, selected machines or applications should be modelled according to their energy consumption profile. These models should be trainable based on the measurements and used to observe abnormal operations.
Tutors: Hackelöer and Freiburg

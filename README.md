# Antimicrobial Profile
Application for antimicrobial profile generation

Basic antibiotics, bacteria and antibiotic sensibility test database. This application comprises a backend REST API written in Go and a simple frontend for registering data from sensibility tests.

This application allows registering of:

- Antibiotics
- Bacteria
- Patients locations
- Collected materials
- Sensibility tests

A sensibility test contains data of patient's location, which material was collected and what bacteria was found in it. Then a series of antibiotics are tested against this bacteria. The test has then a result of sensible or resistant, if the antibiotic is effective or not against this bacteria.

The data collected can then be summarized in forms of tables and/or charts, which are of extreme importance to the Hospital Infection Control Comittee for controlling the occurence of resistant bacterial infections in the different sectors of the hospital.
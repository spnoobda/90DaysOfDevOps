TASK 1:

<img width="1027" height="413" alt="Screenshot from 2026-03-14 23-23-27" src="https://github.com/user-attachments/assets/49961f91-5d0e-48bf-bb87-4a0468817c82" />
<img width="1451" height="806" alt="Screenshot from 2026-03-14 23-23-50" src="https://github.com/user-attachments/assets/5f50c90f-5b14-4c2a-bb29-6efa22aba174" />
<img width="675" height="193" alt="Screenshot from 2026-03-14 23-31-22" src="https://github.com/user-attachments/assets/b64f603b-6e36-40e3-835c-80b495f723a7" />

When a docker container is deleted, the data, since it is saved in the container itself, is also lost

TASK 2:

<img width="1539" height="948" alt="Screenshot from 2026-03-15 20-59-47" src="https://github.com/user-attachments/assets/47a57303-c4da-45a7-9c8a-eacc2390d086" />
<img width="1327" height="846" alt="Screenshot from 2026-03-15 21-00-18" src="https://github.com/user-attachments/assets/70c5fb95-5e3e-4808-baac-1270d1de93ca" />

Named volumes help to keep data persistent. So even if the container gets deleted, the data is not lost. The data in named volumes is stored by docker itself. 

TASK 3:

<img width="955" height="722" alt="Screenshot from 2026-03-16 00-26-32" src="https://github.com/user-attachments/assets/84850551-a9b4-434d-86bd-3c65d104d59a" />
<img width="1327" height="520" alt="Screenshot from 2026-03-16 00-25-07" src="https://github.com/user-attachments/assets/e3207c2a-7b3c-4ade-b1f5-f1d9a3a5ec61" />
<img width="1327" height="520" alt="Screenshot from 2026-03-16 00-26-08" src="https://github.com/user-attachments/assets/05f4348a-5a79-4307-82bf-fe15b4263df6" />

Bind mounts are better for development purpose. Named volumes are better for storing data/ persistent data. The data in bind mounts are stored locally in the machine. While in named volumes, the data is stored and managed by docker.

TASK 4:

<img width="654" height="839" alt="Screenshot from 2026-03-16 22-57-32" src="https://github.com/user-attachments/assets/a2db9528-9f34-4b4b-8f9e-4d1fab6aea04" />
<img width="686" height="238" alt="Screenshot from 2026-03-16 22-58-01" src="https://github.com/user-attachments/assets/e3fdfc78-a6cf-4f3a-a939-2f4d0caf09de" />
<img width="686" height="238" alt="Screenshot from 2026-03-16 22-58-24" src="https://github.com/user-attachments/assets/5f7c18f9-4ddd-41d1-b0bf-bea377279263" />
<img width="686" height="238" alt="Screenshot from 2026-03-16 22-58-47" src="https://github.com/user-attachments/assets/1104b875-d1ea-4725-bc5c-26350504ae8b" />
<img width="686" height="546" alt="Screenshot from 2026-03-16 22-59-19" src="https://github.com/user-attachments/assets/76b7fac3-2fff-46ca-8adb-813115063d46" />

Containers can only communicate with the help og IP address of the other container

<img width="784" height="153" alt="Screenshot from 2026-03-16 22-59-40" src="https://github.com/user-attachments/assets/079b7352-15d0-4a98-bb78-f3484547d723" />

Containers cannot ping each other by name in default bridge network

TASK 5:

<img width="734" height="994" alt="Screenshot from 2026-03-17 16-26-07" src="https://github.com/user-attachments/assets/5d3fec39-5fef-443a-8868-db941daadcd9" />
<img width="996" height="994" alt="Screenshot from 2026-03-17 16-26-38" src="https://github.com/user-attachments/assets/a6c93db5-5fe7-4cbb-bb08-532af06841e2" />

In a custom network, the docker provides an internal DNS resolution where the names of the containers are resolved to their respective container names. That is why, communication can happen by directly using the names of the containers.

TASK 6:

<img width="996" height="392" alt="Screenshot from 2026-03-17 23-35-22" src="https://github.com/user-attachments/assets/47bafc15-32b8-4363-9f6b-b41bf586789d" />
<img width="1013" height="994" alt="Screenshot from 2026-03-17 23-51-21" src="https://github.com/user-attachments/assets/ff259ef0-ffdb-494c-8200-e05e1772bc24" />
<img width="1013" height="994" alt="Screenshot from 2026-03-17 23-51-34" src="https://github.com/user-attachments/assets/a3cf3eff-96b3-4ff5-9f93-e9c7f0b89aa0" />



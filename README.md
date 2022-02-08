# OSCP-Exam-rules

#Proctoring Tool Student Manual \
https://help.offensive-security.com/hc/en-us/articles/360050299352 \
https://help.offensive-security.com/hc/en-us/sections/360008126631

## Requerimientos del examen
### Exploit Code
1. Sí no se realizaron modificación al exploit, solo ingresar la dirección URL
2. Sí el exploit fue modificado
- El código de explotación modificado
- URl del original exploit
- Comando usado para generar shellcode
- Cambios destacados realizados
- Explicación del los cambios

### Exam Proofs
1. Ingresar al "control panel"
2. Incluir screenshot para documentación.
3. Mostrar el contenido con el comnedo "cat" o"type" desde la original posición.

### Control Panel Submission
Ingresar el contenido de cada local.txt y proof.txt.

### Screenshot Requirements
Para cada local.txt y proof.txt, se debe mostrar su contenido y dirección IP del target usando "ipconfig", "ifconfig" o "ip addr".Incluir privilegios obtenidos.

### Exam Restrictions
No usar lo siguiente:
1. Spoofing (IP, ARP, DNS, NBNS, etc)
2. Commercial tools or services (Metasploit Pro, Burp Pro, etc.)
3. Automatic exploitation tools (e.g. db_autopwn, browser_autopwn, SQLmap, SQLninja etc.)
4. Mass vulnerability scanners (e.g. Nessus, NeXpose, OpenVAS, Canvas, Core Impact, SAINT, etc.)
5. Features in other tools that utilize either forbidden or restricted exam limitations

Herramientas permitidas: \
https://help.offensive-security.com/hc/en-us/articles/4412170923924-OSCP-Exam-Update-01-11-22-FAQ%C2%A0

1. BloodHound
2. SharpHound
3. PowerShell Empire
4. Covenant 
5. Powerview
6. Rubeus
7. evil-winrm
8. Responder (Poisoning and Spoofing is not allowed in the labs or on the exam)
9. Crackmapexec
10. Mimikatz

Solo se puede utilizar en una sola maquina metasploit.

### Metasploit Restrictions
Solo se puede utilizar Metasploit (Auxiliary, Exploit, ay Post)  o Meterpreter contra un solo objetivo. \
Unicamente se puede utilizar en diversar maquinas:
1. multi handler (aka exploit/multi/handler)
2. msfvenom
3. pattern_create.rb
4. pattern_offset.rb

## EXAM INFORMATION
### Exam Connection
1. Descargar el comprimido "exam-connection.tar.bz2" proporcionado vía mail.
2. Extraer contenido
```
tar xvfj exam-connection.tar.bz2
```
4. Conectarse a VPN
```
sudo openvpn OS-XXXXXX-OSCP.ovpn 
```
6. Teclear usuario y contraseña proporcionada vía mail.

### Exam Control Panel
### Machine Reverts (limit 24)
### Exam Proof Filenames
### Point Allocation
### Point Disqualification
1. Usando herramienta restringida
2. Modulos de Metasploit Auxiliary, Exploit y Post en multiples maquinas.
3. Meterpreter en multiples maquinas.
4. Mostrar el contenido de local.txt y proof.txt en "control panel" y "screenshot".
### Suggested Documentation Templates
https://www.offensive-security.com/pwk-online/OSCP-Exam-Report.docx
### Bonus Points
https://help.offensive-security.com/hc/en-us/articles/360046787731-Penetration-Testing-with-Kali-Linux-Reporting

### Internet Connection Issues
SOlo son 23:45 hours, utilizando lo siguiente:
1. Tomar descansos, comida y dormir.
2. Considerar tener un conexion a internet de respaldo.

Enviar correo a "challenges@offensive-security.com" con todo detalle.
Solo se podrá aumentar tiempo de examen si el error se tuvo por infrastructura de offensive.

### Contact Protocol
Problemas de conectividad con cualquier maquina o VPN, contactar con "https://chat.offensive-security.com" o  "help@offensive-security.com". \
Preguntas relacionadas con la documentación y el envío del examen, u otros problemas no relacionados con el examen técnico, deben enviarse a "challenges@offensive-security.com".


## SECTION 3: SUBMISSION INSTRUCTIONS
... Pending
### Submission Checklist:
### Submission Format and Name
### Archive File
### Submission Upload
### Acknowledgement of Receipt
### Additional Required Information
### Results



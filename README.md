# OSCP-Exam-rules
https://help.offensive-security.com/hc/en-us/articles/360040165632

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





# Proctored Exams
## Proctoring Tool Student Manual
https://help.offensive-security.com/hc/en-us/articles/360050299352-Proctoring-Tool-Student-Manual

## ¿Cuáles son los requisitos técnicos para participar en un examen supervisado?
https://help.offensive-security.com/hc/en-us/articles/360040160792-What-are-the-technical-requirements-to-participate-in-a-proctored-exam-

## ¿Qué se espera de mí como estudiante para participar en un examen supervisado?
https://help.offensive-security.com/hc/en-us/articles/360040574491-What-is-expected-of-me-as-a-student-to-participate-in-a-proctored-exam- \
1. INE o pasaporte
2. Identificación escaneada

## ¿Cómo me conecto al supervisor para comenzar mi examen?
https://help.offensive-security.com/hc/en-us/articles/360040160892-How-do-I-connect-to-the-proctor-to-start-my-exam-

## ¿Puede el supervisor escucharme durante el examen?
No

## ¿Cuáles son los requisitos previos al examen que el supervisor debe verificar antes de comenzar mi examen?
https://help.offensive-security.com/hc/en-us/articles/360040574991-What-are-the-pre-exam-requirements-the-proctor-must-verify-before-I-start-my-exam-
1. El supervisor verificará la configuración técnica de su máquina con los requisitos técnicos de su examen.
2. Identificación.
3. El supervisor puede hacer preguntas en la ventana de chat de la herramienta de supervisión.
4. Se le pedirá que escanee la habitación y sus alrededores con su cámara web
5. El supervisor le pedirá que comparta todas sus pantallas y muestre todos los programas en ejecución
6. Una vez conectado a la VPN del examen, el supervisor verificará que solo esté conectado a la VPN del examen y le pedirá que ejecute el script de resolución de problemas.sh, que se incluye en el paquete de conectividad VPN.

## ¿Puedo dormir durante la duración del examen?
Si, se requiere avisar.

## ¿Cuándo comienza mi examen supervisado?
https://help.offensive-security.com/hc/en-us/articles/360040160852-When-does-my-proctored-exam-start-
15 minutos antes.

## ¿Completar los pasos previos al examen me dará menos tiempo en el examen real?
https://help.offensive-security.com/hc/en-us/articles/360040574831-Will-completing-the-pre-exam-steps-give-me-less-time-in-the-actual-exam-

## ¿Puedo utilizar auriculares, auriculares o earpods?
https://help.offensive-security.com/hc/en-us/articles/4409993849108-Can-I-use-headphones-earphones-or-earpods-
Si, conectados en la maquina.

## ¿Cuáles son los elementos que están permitidos y no permitidos en mi entorno de examen?
La máquina, pantallas externas que se comparten con la sesión, los libros y notas impresos, el papel y el bolígrafo son los elementos permitidos. No se le permite usar, y no debe haber otros dispositivos electrónicos que no sean su máquina de examen dentro de su área de examen
https://help.offensive-security.com/hc/en-us/articles/4406621212820-What-are-the-items-that-are-allowed-and-not-allowed-in-my-exam-environment-

## ¿Puedo realizar videollamadas o reuniones en mi máquina de examen durante el examen?
https://help.offensive-security.com/hc/en-us/articles/4406628301716-Can-I-conduct-video-calls-or-meetings-on-my-exam-machine-during-the-exam- \
No, solicitar un descanzo.

## ¿Puedo usar otros dispositivos para otros fines durante el examen?
https://help.offensive-security.com/hc/en-us/articles/4406628296724-Am-I-allowed-to-use-another-devices-for-other-purposes-during-the-exam- \
No.

## No recibí mi paquete de conectividad y los detalles de inicio de sesión del examen a la hora de inicio del examen. ¿Ahora que?
https://help.offensive-security.com/hc/en-us/articles/360040574971-I-didn-t-receive-my-connectivity-pack-exam-login-details-at-my-exam-start-time-Now-what-

## ¿Qué pasa si no quiero completar uno de los requisitos previos al examen?
https://help.offensive-security.com/hc/en-us/articles/360040161212-What-if-I-do-not-want-to-complete-one-of-the-pre-exam-requirements-

## ¿Qué pasa si no cumplo con los requisitos, tengo que reprogramar mi examen?
https://help.offensive-security.com/hc/en-us/articles/360040575131-What-if-I-do-not-meet-the-requirements-do-I-have-to-reschedule-my-exam-

## ¿Qué sucede si no me presento a la hora programada para el examen?
https://help.offensive-security.com/hc/en-us/articles/360040575171-What-if-I-do-not-show-up-at-my-scheduled-exam-time-
Tiene una hora de tolerancia.

## ¿Existe un código de vestimenta para un examen supervisado?
https://help.offensive-security.com/hc/en-us/articles/360040161452-Is-there-a-dress-code-for-a-proctored-exam-

## ¿Cómo me comunico con el supervisor durante el examen?
https://help.offensive-security.com/hc/en-us/articles/360040575211-How-do-I-communicate-with-the-proctor-during-the-exam-

## ¿Puedo ver al supervisor durante el examen en la cámara web?
https://help.offensive-security.com/hc/en-us/articles/360040161532-Can-I-see-the-proctor-during-the-exam-on-webcam-

## ¿Estará el supervisor conmigo durante todo el examen?
https://help.offensive-security.com/hc/en-us/articles/360040161552-Will-the-proctor-be-with-me-for-the-full-duration-of-the-exam-

## ¿Puedo tomar descansos durante el examen?
https://help.offensive-security.com/hc/en-us/articles/360040575251-Can-I-take-breaks-during-the-exam- \
Si

## ¿Pueden otras personas entrar a la habitación cuando tomo mi examen?
https://help.offensive-security.com/hc/en-us/articles/360040575571-Can-other-people-enter-the-room-when-I-take-my-exam- \
La entrada de otra persona durante su examen no descalifica su intento de examen. Si alguien ingresa a la sala durante su examen, el supervisor documentará la duración de la visita en su informe de observación. Puede conversar con la otra persona, sin embargo, no debe revelar ningún detalle del examen.

## ¿Puedo terminar mi examen antes de tiempo?
https://help.offensive-security.com/hc/en-us/articles/360040161932-Can-I-end-my-exam-early-

## ¿Qué sucede si me desconecto del software de supervisión?
https://help.offensive-security.com/hc/en-us/articles/360040161972-What-happens-if-I-get-disconnected-from-the-proctoring-software- \
Si está desconectado por un período breve (un par de minutos), el supervisor tomará nota. Sin embargo, si está desconectado por un período de tiempo más largo, su VPN se detendrá. Solo se reactivará una vez que vuelva a unirse a la sesión. Si tiene problemas para volver a conectarse correctamente, comuníquese con nosotros enviando una solicitud de asistencia. \
https://help.offensive-security.com/hc/en-us/requests/new

## ¿Qué sucede si el software de supervisión deja de responder?
Cierre la ventana del navegador (sesión), luego reinicie la sesión de supervisión. Una vez que se haya vuelto a conectar, notifique al supervisor que la aplicación dejó de responder y la reinició. Si tiene problemas para volver a conectarse correctamente, comuníquese con nosotros enviando una solicitud de asistencia. \
https://help.offensive-security.com/hc/en-us/requests/new

## ¿Tengo que dejar la transmisión de la cámara web abierta en todo momento?
https://help.offensive-security.com/hc/en-us/articles/360040162092-Do-I-have-to-leave-the-webcam-feed-open-at-all-times-  \
Su cámara web no debe estar obstruida y colocada correctamente, mostrando su rostro y al menos la mitad de su cuerpo, y el entorno real mientras realiza el examen. Sin embargo, puede pausarlo durante su descanso. No cierre la pestaña o la ventana del navegador, ya que desconectará la sesión de supervisión y su examen VPN puede estar en pausa por nuestra parte. Hay una opción para ocultar la transmisión de su cámara web en la ventana de la página de supervisión si no desea que la abran.

## ¿Qué pasa si tengo preguntas durante el examen, puedo preguntarle al supervisor?
Sí tu puedes. Sin embargo, el supervisor solo puede ayudarlo con cualquier consulta relacionada con la supervisión. Si tiene preguntas relacionadas con el examen, siga el Protocolo de contacto que se indica en la guía del examen. \
https://help.offensive-security.com/hc/en-us/articles/360040162132-What-if-I-have-questions-during-the-exam-can-I-ask-the-proctor-

## ¿Qué hace exactamente el supervisor durante el examen?
https://help.offensive-security.com/hc/en-us/articles/360040162152-What-exactly-is-the-proctor-doing-during-the-exam-

## ¿Quiénes son los supervisores y para quién trabajan?
https://help.offensive-security.com/hc/en-us/articles/360040575891-Who-are-the-proctors-and-who-do-they-work-for-




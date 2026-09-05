# Actividad-6-miguel-m.
## 1) Lee la Información que se compartió en la misma guía y desarrolla un resumen de lo entendido, anexo agrega pantallazos de la información del paso a paso que se te muestra.
Lo que se puede leer en la guia es como actualizar mi dispositivo,  y ver que no tengan virus pero tambien se menciona como verificar si estan cifrados mis archivos, como instalar programas de manera segura  y ver que mi dispositivo tenga un bloqueo de acceso, desafortunamente la guia unicamente habla a detalle de las primeras 2, mi entendimiento es que es recomendable estar actualizado porque si llegamos a tener versiones viejas del sistema es mucho mas facil y probable que alguien pueda entrar en nuestros archivos por culpa del rapido crecimiento de los "hackers", pero asi mismo los sitemas intentan mantenerse al la par para no ser tan sencillos de vulnerar, estar actualizado tampoco nos vuelve inmunes pero por lo menos disminuye las posibilidades , tambien debemos procurar no causarnos daño a nosotros mismo a travez de enlaces sospechosos o intentando instalar aplicaciones de sitios no verificados esto obviamente podria "infectarnos" de un virus o varios.

## 1.1) como actualizar tus dispositivos 
primero nos metemos a configuracion

<img width="554" height="312" alt="image" src="https://github.com/user-attachments/assets/aca4d35f-b18d-4507-b987-f8fa48724134" />

luego nos metemos en "windows update" y verificamos estar con la ultima actualizacion


<img width="1600" height="890" alt="image" src="https://github.com/user-attachments/assets/23cbdcd4-3afa-4e33-b0e1-64897ff7346a" />
en este caso el sistema esta al dia, pero si no pues la idea seria buscar actualizaciones y descargarlas, tambien existe la opcion de actualizar el sistema automaticamente pero si no estoy mal ya es una funcion implementada en la mayoria de dispositivos modernos

## 1.2) Como comprobar que tus dispositivos estan protegidos (antivirus)
nuevamente entramos a la configuracion


<img width="554" height="312" alt="image" src="https://github.com/user-attachments/assets/aca4d35f-b18d-4507-b987-f8fa48724134" />

pero en esta ocasion entramos a la privacidad y seguridad


<img width="251" height="45" alt="image" src="https://github.com/user-attachments/assets/92406e48-721a-4839-a529-060c3ed44cac" />
 y buscamos la opcion de "seguridad e windows"

 <img width="1082" height="173" alt="image" src="https://github.com/user-attachments/assets/4e4e918a-8985-4d3e-8db8-9235013e174d" />

ingresamos a la opcion de "proteccion contra virus y amenazas"

<img width="1149" height="256" alt="image" src="https://github.com/user-attachments/assets/b2c42043-ef3e-473d-b3b0-efdd7fa20e10" />

despues hacemos un examen rapido 

<img width="552" height="480" alt="image" src="https://github.com/user-attachments/assets/b697e2dd-0fde-40b9-b603-8842006394fd" />

este se encargara de revisar todos los archivos y nos alertara de cualquier rareza

<img width="549" height="198" alt="image" src="https://github.com/user-attachments/assets/0a002e0d-ac24-4df0-9cd3-770693b2dda1" />

en este caso salio bien sin ninguna amenaza detectada

<img width="447" height="373" alt="image" src="https://github.com/user-attachments/assets/390619a4-7bdc-470f-8624-ad85cc6aaf08" />

## 2) ¿Qué es VirtualBox?, ¿Qué es WSL?, ¿Qué es VMWARE?, ¿Qué es QEMU? Y ¿Qué es KVM?. Desarrolle la búsqueda de cada una de las tecnologías presentadas y proceda a explicar sus características, diferencias, ventajas y aplicaciones.

Explicacion general creada por IA 
# Glosario de Tecnologías de Virtualización y Entornos Operativos

> 🤖 **Nota de autoría:** Este documento fue generado de forma automática por un asistente de Inteligencia Artificial (IA) a petición del usuario.

Este documento ofrece un resumen rápido sobre el funcionamiento y propósito de **VirtualBox**, **WSL**, **VMware**, **QEMU** y **KVM**.

---

### 📦 VirtualBox
* **Definición:** Es un software de virtualización de tipo 2 (se ejecuta sobre un sistema operativo principal) desarrollado por Oracle.
* **Propósito:** Permite crear máquinas virtuales (VM) para instalar y usar sistemas operativos completos de forma aislada.
* **Características:** Es gratuito, de código abierto y muy popular entre usuarios domésticos por su interfaz visual intuitiva.

### 🐧 WSL (Windows Subsystem for Linux)
* **Definición:** Es una característica de Windows que permite ejecutar un entorno de Linux nativo directamente en Windows, sin la carga de una máquina virtual tradicional.
* **Propósito:** Está diseñado para desarrolladores que necesitan herramientas de línea de comandos de Linux dentro de Windows.
* **Características:** Traduce de forma eficiente las llamadas del sistema de Linux para el núcleo de Windows, ofreciendo un gran rendimiento.

### 🏢 VMware
* **Definición:** Es una familia de productos de virtualización (como VMware Workstation o ESXi) orientados tanto al usuario de escritorio como a entornos corporativos.
* **Propósito:** Crear entornos virtuales de alto rendimiento y estabilidad comercial para servidores y estaciones de trabajo.
* **Características:** Destaca por su optimización avanzada de recursos, gestión de redes complejas y herramientas empresariales.

### ⚙️ QEMU (Quick Emulator)
* **Definición:** Es un emulador y virtualizador de código abierto extremadamente flexible.
* **Propósito:** Capaz de emular arquitecturas de hardware completamente diferentes (por ejemplo, ejecutar código ARM en un ordenador x86).
* **Características:** Funciona mediante emulación pura por software, lo que puede ser lento a menos que se combine con un acelerador por hardware.

### 🖥️ KVM (Kernel-based Virtual Machine)
* **Definición:** Es un módulo que convierte al propio núcleo de Linux en un hipervisor de tipo 1 (con acceso directo al hardware).
* **Propósito:** Gestionar máquinas virtuales en Linux con un rendimiento prácticamente nativo.
* **Características:** Suele combinarse con **QEMU**, donde KVM acelera el procesador/memoria y QEMU se encarga de simular los componentes virtuales de disco, red y periféricos.

## Comparacion

| Tecnología | caracteristica | Diferencias  | Ventajas  | Aplicaciones |
| :--- | :--- | :--- | :--- | :--- |
| **VirtualBox** | es gratuito y de codigo abierto | Gratuito, emula hardware completo por software mediante una interfaz gráfica sencilla. | • Fácil de usar.<br>• Multiplataforma (Windows, macOS, Linux).<br>• Gran comunidad y soporte. | • Estudiantes y aprendizaje.<br>• Probar sistemas operativos de forma rápida.<br>• Entornos de desarrollo aislados simples. |
| **WSL** | Subsistema / Traducción de llamadas | No es una máquina virtual completa; comparte el núcleo o corre un núcleo Linux optimizado dentro de Windows. | • Consumo mínimo de recursos.<br>• Rendimiento muy rápido.<br>• Integración directa con el sistema de archivos de Windows. | • Desarrolladores en Windows que necesitan herramientas Linux (Docker, Git, Bash).<br>• Entornos de programación web. |
| **VMware** | Hipervisor Tipo 1 (ESXi) o Tipo 2 (Workstation) | Software comercial de alto rendimiento con gestión avanzada de redes y recursos empresariales. | • Máximo rendimiento gráfico y de CPU.<br>• Muy estable y robusto.<br>• Funciones avanzadas de clonación y snapshots. | • Entornos corporativos y centros de datos.<br>• Administradores de sistemas y redes profesionales.<br>• Pruebas de software a gran escala. |
| **QEMU** | Emulador y Virtualizador puro | Puede emular arquitecturas de hardware distintas a la del procesador real (ej. emular ARM en x86). | • Flexibilidad extrema.<br>• Soporta casi cualquier arquitectura.<br>• Es de código abierto y ligero. | • Desarrollo de sistemas embebidos y firmware.<br>• Depuración de kernels.<br>• Ejecución de software antiguo o de otros procesadores. |
| **KVM** | Hipervisor Tipo 1 (Integrado en Linux) | Convierte el núcleo de Linux en un hipervisor. Se usa junto con QEMU para el hardware virtual. | • Rendimiento casi nativo (acceso directo al hardware).<br>• Excelente escalabilidad.<br>• Integrado en el ecosistema Linux. | • Servidores en la nube (infraestructura cloud).<br>• Virtualización empresarial en servidores Linux.<br>• Usuarios avanzados de Linux. |





  








 



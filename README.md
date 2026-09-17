
# 🧠 C/C++ Embebido — STM32F334R8

Repositorio enfocado al estudio y práctica de programación en C/C++ para sistemas embebidos, utilizando como plataforma de desarrollo la STM32F334R8.


📚 Estructura teorica

🧩 1. Fundamentos de Hardware y Registros
*  Registros de memoria
*  Mapa de memoria del STM32
*  Registros de periféricos
*  Lectura y escritura de registros
*  Operaciones a nivel de bits
*  Máscaras de bits
*  Configuración de periféricos mediante registros
*  Diferencia entre HAL, LL y acceso directo a registros

🚀 2. DMA — Direct Memory Access
*  DMA
*  ¿Qué es DMA?
*  Transferencias Memoria ↔ Periférico
*  Transferencias Memoria ↔ Memoria
*  Canales y solicitudes DMA
*  Transferencias de datos
*  Modo circular
*  DMA + ADC
*  DMA + UART
*  Ventajas frente a transferencias mediante CPU

🎚️ 3. Comparadores Analógicos (COMP) + DAC
*  Comparadores analógicos
*  Configuración del COMP
*  Comparación de señales analógicas
*  DAC — Digital to Analog Converter
*  Conversión digital → analógica
*  COMP + DAC
*  Generación y comparación de niveles de referencia
*  Aplicaciones en sistemas de control y adquisición

⚡ 4. ADC de Alta Velocidad + Triggering

*  ADC — Analog to Digital Converter
*  Resolución y cuantización
*  Frecuencia de muestreo
*  Tiempo de conversión
* ADC de alta velocidad
*  Triggering por hardware
*  Conversión continua
*  Conversión mediante eventos externos
*  ADC + Timer
*  ADC + DMA
*  Adquisición de señales en tiempo real

🧠 5. NVIC Avanzado + Latencia de Interrupciones

*  NVIC — Nested Vectored Interrupt Controller
*  Interrupciones del microcontrolador
*  Vector Table
*  Prioridades de interrupción
*  Preemption
*  Subprioridades
*  Latencia de interrupción
*  Tiempo de respuesta
*  Secciones críticas
*  ISR — Interrupt Service Routine
*  Optimización de interrupciones
*  Minimización de latencia

⏱️ 6. Timers

*  Timers
*  Arquitectura de los temporizadores
*  Prescaler
* Counter
*  Auto-Reload Register
*  Periodicidad
*  Timer Interrupts
*  Input Capture
*  Output Compare
*  PWM
*  Medición de frecuencia
*  Medición de periodo y tiempo
*  Timer + ADC
*  Timer + DMA

🕐 7. System Tick Timer

*  System Tick Timer
*  ¿Qué es SysTick?
*  Generación de interrupciones periódicas
*  Base de tiempo del sistema
*  Millisegundos y microsegundos
*  Delays
*  Timeouts
*  Temporización no bloqueante
*  SysTick + interrupciones
*  SysTick como base para sistemas de tiempo real

🤖 8. Conceptos de RTOS

*  ¿Qué es un RTOS?
*  Sistemas de tiempo real
*  Tasks / Threads
*  Scheduler
* Periodicidad de tareas
*  Prioridades
*  Mutex
*  Semáforos
*  Queues
*  Event Groups
*  Software Timers
*  Critical Sections
*  Interacción entre interrupciones y tareas
*  FreeRTOS
*  FreeRTOS
*  Creación de Tasks
*  Prioridades
* vTaskDelay()
*  Mutex
*  Semáforos
*  Queues
* Event Groups
* Software Timers
* Comunicación ISR ↔ Task
* Análisis básico de planificación


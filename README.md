# Automation-IA-Avanzado-TP-Final
Automation IA Avanzado TP Final

EJERCICIO
Componente A: El Ecosistema Técnico (Los Workflows en n8n)
Un sistema integrado en n8n (versión comunitaria o nube en plan de pruebas/freemium) que automatice un proceso en segundo plano ante un estímulo inicial, estructurado bajo el patrón Manager-Worker:
1.	Petición asincrónica: Un disparador (Webhook o Chat Trigger) que reciba la solicitud, responda de inmediato al servidor externo con un código de recepción rápida y procese la lógica analítica en segundo plano.
2.	Auditoría Activa (QA Automatizado): La propuesta de respuesta del agente debe pasar de forma obligatoria por el sub-workflow supervisor AI-as-a-Judge antes de consolidar datos o registrar acciones comerciales. Si la nota es inferior al umbral mínimo establecido (ej. exactitud_factual < 4 en la rúbrica JSON Schema), se congela la autonomía en producción y se desvía a revisión humana mediante una cola de aprobación (Human-in-the-loop).
3.	Notificación final: Despacho del resultado validado por un canal de comunicación de la empresa que cuente con API de acceso freemium o gratuito (por ejemplo, hilos de borradores automatizados en Gmail, mensajes de registros en un bot oficial de Telegram o canales internos de Slack).
Componente B: La Documentación de Defensa (DMSA)
Un informe de consultoría ejecutiva que valide las decisiones del diseño del sistema, organizado bajo estas cuatro secciones fijas:
•	Sección 1: Portada y Resumen Ejecutivo: Título del proyecto, autor, cohorte (2026) y descripción del problema real de negocio resuelto.
•	Sección 2: Diagrama de Arquitectura de n8n: Capturas nítidas del lienzo general explicando la interconexión modular distributiva, el flujo de datos, la base de memoria persistente de largo plazo y el acople contextual.
•	Sección 3: Reporte de Auditoría y Rúbricas: Muestra de 3 ejemplos reales de respuestas de la IA evaluadas, criticadas y puntuadas en formato JSON plano por el supervisor.
•	Sección 4: Justificación Financiera (Métricas de ROI): Cuantificación del coste estimado mensual en tokens (optimizando la ventana de contexto mediante modelos económicos como GPT-4o-mini o Claude 3 Haiku) versus el coste de labor humana evitado, demostrando la rentabilidad del sistema.

# En la carpeta se encuentran los siguientes archivos:

# Imagenes:

-orquestador inmobiliario multiagente.jpg
Es la imagen del core principal desde ahí se llama a los multiagentes que contendrá el TP

-juez y auditoria.jpg
Es la imagen del agente de juez y auditoria

-worker alquilar.jpg
Es la imagen de uno de los worker que llama el orquestador. En particular se encarga de los alquileres

-worker consulta.jpg
Es la imagen de uno de los worker que llama el orquestador. En particular se encarga de las consultas enviadas por los clientes sobre disponibilidades

-worker vender.jpg
Es la imagen de uno de los worker que llama el orquestador. En particular se encarga de las ventas

-worker ver.jpg
Es la imagen de uno de los worker que llama el orquestador. En particular se encarga de las visitas

# Jsons:

-Orquestador Inmobiliario Multiagente v11.json
-Juez y Auditoríav11.json
-Worker Alquilar Departamento v11.json
-Worker Consulta General v11.json
-Worker Vender Departamento v11.json
-Worker Ver Departamento v11.json

# PDF:
Lopez_Spinelli_Rodolfo_ProyectoFinal_AI_Experto.pdf
Archivo que compila toda la información del proyecto final

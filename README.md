# Open-Ionic-Coanda-Drone
# ⚡ Open-Ionic-Coanda-Drone (Tricóptero de Propulsión EHD)

Este repositorio contiene el diseño conceptual, la memoria de ingeniería y las especificaciones técnicas para un **vehículo aéreo no convencional (UAV) de propulsión 100% de estado sólido (sin piezas móviles externas)**, impulsado por **Viento Iónico (Electrohidrodinámica - EHD) y Efecto Coandă**.

Originalmente concebido bajo un enfoque acústico, el proyecto evolucionó hacia la física del plasma atmosférico de baja temperatura, logrando multiplicar por cuatro la eficiencia energética, eliminar por completo las vibraciones mecánicas y reducir drásticamente los costos de fabricación.

---

## 🔬 Principio de Operación

A diferencia de los drones tradicionales que dependen de hélices mecánicas, este dispositivo utiliza **tres impulsores modulares en forma de campanas dobles de policarbonato (12 cm de diámetro)** que operan de forma silenciosa:

1. **Generación de Viento Iónico:** Una corona de ánodos de acero inoxidable tallados en diente de sierra ioniza las moléculas de aire ambiental usando un campo eléctrico masivo de **30,000 Voltios (30 kV CC)**.
2. **Aceleración Electrostática:** Los iones positivos son repelidos con violencia hacia un cátodo multi-anillo de aluminio situado a 35 mm de distancia. En su trayectoria, los iones chocan con miles de millones de moléculas de aire neutro, arrastrándolas por puro impacto cinético.
3. **Amplificación por Efecto Coandă:** Este flujo continuo de aire es inyectado en un canal intermedio de 4 mm y eyectado por una ranura anular inferior de 2.5 mm a **120 m/s**. El flujo lame la curvatura de la campana exterior, generando sustentación y empuje vertical asimétrico de alta eficiencia.
4. **Cosecha de Energía de Estado Sólido:** Películas termoeléctricas flexibles (f-TEG) de telururo de bismuto y parches de macro-fibra piezoeléctrica en el chasis absorben los diferenciales térmicos y vibraciones parásitas ambientales, reinyectando corriente continua al sistema.

---

## 🛠️ Especificaciones Técnicas del Prototipo

| Parámetro | Especificación |
| :--- | :--- |
| **Configuración** | Tricóptero EHD (3 Impulsores de 12 cm de diámetro) |
| **Dimensiones Globales** | 35 - 40 cm de diámetro total |
| **Masa Total del Vehículo** | 1.5 kg (Incluyendo circuito de alta tensión y batería) |
| **Voltaje de Operación Sólida** | Modulable digitalmente entre 18 kV y 32 kV CC |
| **Consumo Eléctrico de Vuelo** | **120 - 150 Vatios (W)** (Reducción del 75% vs. diseño acústico) |
| **Velocidad de Escape del Aire** | ~120 m/s (432 km/h) en la tobera anular |
| **Autonomía de Vuelo Estimada** | **35 a 45 minutos** (Con batería LiPo 6S de 4500mAh) |
| **Velocidad Máxima Horizontal** | 80 - 110 km/h (Limitación aerodinámica por despegue Coandă) |
| **Protocolo de Blindaje Eléctrico** | Distancia crítica de 12 cm + Aislamiento dieléctrico epoxi + Jaula de Faraday de Aluminio |

---

## 💳 Estimación de Costos del Proyecto (BOM)

Al eliminar el mecanizado de metales exóticos y remover los costosos transductores acústicos industriales, el prototipo es altamente viable para laboratorios y entusiastas independientes:

*   **Impulsores y Electrodos (Policarbonato 3D + Ánodos Serrados):** $150.00 USD
*   **Chasis Estructural (Fibra de Carbono con aislamiento dieléctrico):** $90.00 USD
*   **Electrónica de Conmutación y Ferritas (Inversores ZVS 150 kHz):** $120.00 USD
*   **Cascadas Multiplicadoras Cockcroft-Walton (Diodos y condensadores rápidos):** $180.00 USD
*   **Computadora de Vuelo y Sensores (Controlador avanzado STM32 H7):** $250.00 USD
*   **Sistema de Alimentación (Batería LiPo Tattu 6S 4500mAh 50C):** $130.00 USD
*   **Blindaje, Jaula de Faraday y Geles Aislantes:** $40.00 USD
*   **Cableado Especial de Silicio para Alta Tensión (Hasta 40kV) y Conectores:** $60.00 USD

💰 **COSTO TOTAL ESTIMADO DE MATERIALES (MVP):** **$1,020.00 USD**

---

## 🕊️ Licencia y Filosofía Abierta

Este proyecto se libera bajo la licencia **CERN Open Hardware Licence (CERN-OHL)** y **Creative Commons BY-SA**. 

El conocimiento recopilado en los planos adjuntos pertenece al mundo. Eres libre de descargar los diagramas del multiplicador de voltaje, clonar la arquitectura del chasis y bifurcar el firmware de estabilidad (basado en *PX4 Autopilot*). La única condición obligatoria es que **cualquier mejora, prototipo derivado o desarrollo basado en este diseño debe mantenerse público, gratuito y bajo estos mismos términos de atribución**.

---
*¿Eres apasionado de la propulsión electrohidrodinámica? Ayúdanos a refinar las matrices de modulación PWM de kilovoltios abriendo un "Issue" o compartiendo tus simulaciones en la sección de discusión del repositorio.*


# semana2-Fontalvo
# Proyecto Semana 2

## 📂 Contenido

- **README.md** → Resumen ejecutivo del proyecto.  
- **comparacion_arquitecturas.xlsx** → Tabla comparativa entre ATmega48P y PIC16F877A.  
- **evolucion_tecnologica.pdf** → Documento sobre evolución tecnológica.  
- **calculos_consumo.md** → Cálculos de consumo energético.  
- **investigacion_evolucion_pic.md** → Estudio comparativo de la evolución PIC16F → PIC18F → PIC32.  
- **moore_pic.png** → Gráfico sobre la Ley de Moore aplicada a microcontroladores.  
- **moore_pic_data.xlsx** → Datos de soporte para el gráfico.  
- **datasheets/** → Carpeta con hojas técnicas (PDFs descargados).  

# ⚡ Cálculos de consumo energético

En este archivo se registran los cálculos relacionados con consumo de energía de los microcontroladores estudiados.  

## Fórmulas generales
- Potencia: `P = V * I`  
- Energía: `E = P * t`  
- Consumo por MHz ≈ Corriente / Frecuencia  

## Ejemplo de cálculo
Si un MCU consume **15 mA** a **5V** y trabaja a **20 MHz**:

- Potencia = `5V * 0.015A = 0.075 W`  
- Consumo por MHz = `15 mA / 20 MHz = 0.75 mA/MHz`  

# 🚀 Evolución de la familia PIC (PIC16F → PIC18F → PIC32)

## 🔹 Tamaño del die y proceso de fabricación
- PIC16F → procesos CMOS clásicos (micrón-class).  
- PIC18F → procesos submicrónicos, mejoras en consumo (nanoWatt/XLP).  
- PIC32 → procesos más modernos, más memoria y periféricos.

## 🔹 Consumo por MHz
- PIC16F → consumo proporcional a frecuencia/voltaje.  
- PIC18F → nanoWatt/XLP reduce consumo en Idle/Sleep.  
- PIC32 → más consumo absoluto, pero más rendimiento por ciclo.

## 🔹 Periféricos
- PIC16F: timers, ADC, USART, SPI/I²C, PWM.  
- PIC18F: USB, más ADC, prioridades en interrupciones.  
- PIC32: 32-bit, DMA, caches, USB OTG, Ethernet, CAN.

## 🔹 Precios actuales
- PIC16F877A → ~US$ 7.49  
- PIC18F2550 → ~US$ 6.54  
- PIC32MX320 → ~US$ 5–6  

---

## 📊 Tabla resumen

| Familia | Año aprox. | Flash (KB) | Características clave | Precio aprox. |
|---------|------------|------------|-----------------------|---------------|
| PIC16F877A | 2003 | 14 KB | Básico, periféricos esenciales | ~7.5 USD |
| PIC18F2550 | 2006 | 32 KB | USB, nanoWatt, mayor flexibilidad | ~6.5 USD |
| PIC32MX320 | 2008 | 256 KB | 32-bit MIPS, DMA, Ethernet, USB OTG | ~5–6 USD |
# 📑 Carpeta datasheets
[ATMEGA48P.PDF](https://github.com/user-attachments/files/22163042/ATMEGA48P.PDF)
[PIC16F877A.PDF](https://github.com/user-attachments/files/22163043/PIC16F877A.PDF)

 

# Cisco Network Laboratory

Repositorio de prácticas de laboratorio realizadas en Cisco Packet Tracer para la clase de Redes de Computadoras. Aquí encontrarás archivos de configuración, diagramas de red y recursos relacionados con las prácticas desarrolladas.

---

## Tabla de Contenidos

- [Prácticas Básicas](#prácticas-básicas)
- [Prácticas Avanzadas](#prácticas-avanzadas)
- [Ejercicios Extra](#ejercicios-extra)

---

## Prácticas Básicas

### Práctica 1: Introducción a Redes Básicas
Configuración inicial de dispositivos de red y conectividad básica.

![Práctica 1](https://github.com/CielitoM/Cisco/assets/159088152/1eb930f5-5e6b-47cd-a79f-758285124ac5)

---

### Práctica 2: Configuración de Switches
Implementación de configuraciones básicas de switches y gestión de puertos.

![Práctica 2](https://github.com/CielitoM/Cisco/assets/159088152/9b89fcca-2059-4441-9840-d989fd8611db)

---

### Práctica 3: Topologías de Red
Diseño e implementación de diferentes topologías de red.

<img width="514" height="344" alt="Práctica 3" src="https://github.com/user-attachments/assets/af74e76b-9795-4c9e-b6a9-c784ed6c0f78" />

---

### Práctica 4: Enrutamiento Básico
Configuración de routers y tablas de enrutamiento estático.

![Práctica 4](https://github.com/CielitoM/Cisco/assets/159088152/15c5273d-49cb-4da0-905c-699acfd8ec0b)

---

### Práctica 5: Redes Segmentadas
Implementación de segmentación de red y control de tráfico.

<img width="784" height="659" alt="Práctica 5" src="https://github.com/user-attachments/assets/aa0ddf9b-d046-4395-9d7b-b934c008ad5b" />

---

### Práctica 6: Configuración Avanzada de Switches
Gestión avanzada de switches y optimización de red.

<img width="964" height="619" alt="Práctica 6" src="https://github.com/user-attachments/assets/50c69d51-67c5-48e6-9d57-ed6ccf671156" />

---

### Práctica 7: Protocolos de Enrutamiento
Implementación de protocolos de enrutamiento dinámico.

<img width="768" height="397" alt="Práctica 7" src="https://github.com/user-attachments/assets/b412d72e-91d7-44a5-9a1d-ba47b555930f" />

---

### Práctica 8: Redes de Área Extendida
Configuración de conexiones WAN y enlaces de larga distancia.

<img width="1199" height="446" alt="Práctica 8" src="https://github.com/user-attachments/assets/897e8a2b-e409-4b15-b82f-d5b41dec06bb" />

---

## Prácticas Avanzadas

### Práctica 9: VLANs y Segmentación Avanzada

Implementación completa de VLANs en una red empresarial, incluyendo configuración de trunking y enrutamiento entre VLANs.

#### Topología Principal
<img width="973" height="495" alt="Topología VLAN" src="https://github.com/user-attachments/assets/c065eefc-c0fd-4d0c-bde2-348e15ec83c5" />

#### Configuración de Red
<img width="964" height="583" alt="Configuración VLANs" src="https://github.com/user-attachments/assets/3d4434fc-8cbf-41f4-a223-f92d0d9bc45c" />

#### Diagrama de Conexiones
<img width="1117" height="529" alt="Diagrama de Conexiones" src="https://github.com/user-attachments/assets/e30241e5-23fa-4fc6-b471-b3872b8053af" />

#### Tablas de Configuración

**Configuración de VLANs:**
<img width="919" height="223" alt="Tabla VLANs 1" src="https://github.com/user-attachments/assets/231335ca-9de1-4c85-9999-3f82c562b56b" />
<img width="919" height="224" alt="Tabla VLANs 2" src="https://github.com/user-attachments/assets/10498f93-225f-41d0-8dd8-aa2e4d42e3db" />

**Asignación de Puertos:**
<img width="917" height="144" alt="Puertos 1" src="https://github.com/user-attachments/assets/48f17076-ba29-4207-be56-a3594009b090" />
<img width="919" height="168" alt="Puertos 2" src="https://github.com/user-attachments/assets/430eeb7c-c7a2-4ed4-b905-0c85f62550af" />

#### Caso Hipotético: División de Casa Central en 2 VLANs

**Diagrama del Caso:**
<img width="289" height="373" alt="Caso Hipotético" src="https://github.com/user-attachments/assets/77472738-6b62-470a-ac80-dd4db7ccb30e" />

**Configuración Implementada:**
<img width="973" height="227" alt="Config Casa Central 1" src="https://github.com/user-attachments/assets/3359e9cf-145c-486d-aaeb-4421ef4620b0" />
<img width="916" height="222" alt="Config Casa Central 2" src="https://github.com/user-attachments/assets/404c4de7-0d6c-420f-b5b6-97892384c83f" />
<img width="327" height="266" alt="Resultado" src="https://github.com/user-attachments/assets/172ff392-a363-4a4f-8125-54f105b2c5f1" />

---

### Práctica 10: Interconexión de Redes
Configuración de múltiples routers y enrutamiento entre redes distintas.

<img width="885" height="401" alt="Práctica 10" src="https://github.com/user-attachments/assets/f616ca1f-8029-4d39-b482-0c24ce7288f6" />

---

### Práctica 11: Subnetting y Enrutamiento Complejo

#### Descripción del Proyecto

**Requerimientos:**
- Red base: `10.10.138.0/255.255.254.0`
- IP pública del Router R1: `100.1.1.1/24`
- Gateway: `100.1.1.2`
- LAN 2: máximo 200 usuarios
- Otras LANs: 50 usuarios cada una

**Objetivos:**
1. Determinar las direcciones de cada LAN y sus broadcasts
2. Configurar los routers R1 y R2
3. Elaborar las tablas de enrutamiento

#### Topología de Red
<img width="1012" height="380" alt="Topología Práctica 11" src="https://github.com/user-attachments/assets/fdca5289-a6ef-4e22-92e1-6eae1bb2b032" />

#### Tabla de Subredes
<img width="1274" height="477" alt="Tabla de Subnetting" src="https://github.com/user-attachments/assets/50a9de3b-cdd5-4335-b4ec-7112fad57a74" />

#### Configuración de Routers

**Router R1:**
<img width="918" height="195" alt="Config R1 - Parte 1" src="https://github.com/user-attachments/assets/4c4acefb-cb35-45ce-85f2-a277d07715e3" />
<img width="918" height="142" alt="Config R1 - Parte 2" src="https://github.com/user-attachments/assets/b1e163e8-d3cc-449e-a2c8-44e46a95147c" />

**Router R2:**
<img width="953" height="228" alt="Config R2 - Parte 1" src="https://github.com/user-attachments/assets/e1abdd21-3495-407d-af44-eb35281c4660" />
<img width="955" height="144" alt="Config R2 - Parte 2" src="https://github.com/user-attachments/assets/e2d6f795-807f-466a-a519-9c54a6874f56" />

---

## Ejercicios Extra

### Extra 1: Interconexión mediante VPN

#### Descripción del Escenario
Una LAN en Asunción con IP `192.168.1.0/24` está conectada a un router para salida a internet (IP pública `50.50.50.1/24`, Gateway: `50.50.60.2`).

Un proveedor propone interconectar ambas LANs a través de su WAN mediante una VPN con las siguientes IPs:
- **Extremo 1:** `10.10.1.1/24`
- **Extremo 2:** `10.10.1.2/24`

#### Requerimientos
1. Indicar dispositivos de red necesarios en ambas oficinas
2. Describir los cambios de configuración para implementar la VPN

#### Implementación
<img width="1052" height="505" alt="VPN - Topología" src="https://github.com/user-attachments/assets/a48061d6-2c24-4023-acde-404e5affb86c" />
<img width="1009" height="480" alt="VPN - Configuración" src="https://github.com/user-attachments/assets/28af5ec2-5f3e-43aa-be6c-98a88ae97657" />

---

### Extra 2: Topología de Red con Doble Router

#### Objetivo
Configurar dos routers interconectados con acceso a Internet, garantizando conectividad total (LAN a LAN e Internet).

#### Entregables
- Tabla de Enrutamiento para R1
- Tabla de Enrutamiento para R2
- Configuración CLI genérica para R1
- Configuración CLI genérica para R2

#### Tablas de Enrutamiento

**Router R1:**
<img width="842" height="105" alt="Routing Table R1" src="https://github.com/user-attachments/assets/79bfcf58-9adc-4f5f-a8e1-a0a5df9e1c36" />
<img width="842" height="54" alt="Routing Details R1" src="https://github.com/user-attachments/assets/e16fb507-ac28-4194-a9a5-4a3dfc7b590c" />

**Router R2:**
<img width="842" height="132" alt="Routing Table R2" src="https://github.com/user-attachments/assets/b7114a4b-1625-4e0a-aaf6-69d41a3e288f" />

#### Configuración CLI

**Configuración R1:**
<img width="841" height="152" alt="CLI R1" src="https://github.com/user-attachments/assets/c13f9754-6fa6-458a-a8a6-958606215c1a" />

**Configuración R2:**
<img width="842" height="125" alt="CLI R2" src="https://github.com/user-attachments/assets/18ce55ca-8a4b-4467-8a45-f3ad21a20417" />

---

### Extra 3: Subnetting Avanzado

#### Problema
Dividir la red `10.1.30.0/255.255.248.0` en 4 subredes (A, B, C y D) con los siguientes requerimientos mínimos de hosts:
- **Subred A:** 100 hosts
- **Subred B:** 200 hosts
- **Subred C:** 300 hosts
- **Subred D:** 400 hosts

#### Tabla de Solución
<img width="975" height="136" alt="Tabla Subnetting" src="https://github.com/user-attachments/assets/6396b4b5-6d49-495d-a300-c831650acd9b" />

---

## Recursos Adicionales

### Herramientas Utilizadas
- **Cisco Packet Tracer**: Simulador de redes para diseño y pruebas

### Conceptos Clave
- VLANs y Trunking
- Enrutamiento estático y dinámico
- Subnetting y VLSM
- VPN y túneles seguros
- NAT y PAT

---



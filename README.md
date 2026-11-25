# 🔬 Laboratorio 1: Fundamentos de Redes

Laboratorio desarrollado en la asignatura **Sistemas Colaborativos** (UTP, 2026).

## 🎯 Propósito

Comprender el flujo básico de comunicación en una red local y documentar el proceso de forma reproducible.

## 🗺️ Topología

| Equipo | Interfaz | Dirección IP | Máscara |
|--------|----------|--------------|---------|
| Router R1 | Gi0/0 | 192.168.1.1 | 255.255.255.0 |
| Switch SW1 | VLAN 1 | 192.168.1.2 | 255.255.255.0 |
| PC1 | NIC | 192.168.1.10 | 255.255.255.0 |
| PC2 | NIC | 192.168.1.11 | 255.255.255.0 |

## ⚙️ Procedimiento

1. Armar la topología en Cisco Packet Tracer.
2. Asignar direcciones IP a cada equipo.
3. Verificar conectividad con `ping`.
4. Capturar tráfico ICMP con Wireshark y analizar los paquetes.
5. Documentar resultados y capturas.

## 🧰 Herramientas

- Cisco Packet Tracer
- Wireshark
- Git / GitHub

## 👤 Autor

**Edward Emanuel Villegas Castro** · [LinkedIn](https://www.linkedin.com/in/edward-villegas-b28122427/) · edward.villegas@utp.ac.pa

## 📄 Licencia

Distribuido bajo licencia MIT. Ver [LICENSE](LICENSE).

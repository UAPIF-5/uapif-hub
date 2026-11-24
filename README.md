# UAPIF Hub - Región de Valparaíso (CONAF)

Directorio centralizado de herramientas interactivas HTML para el análisis, pronóstico meteorológico y predicción de incendios forestales de la Corporación Nacional Forestal (CONAF - Región de Valparaíso).

## Estructura de Archivos (8 Herramientas)

```text
uapif-hub/
├── index.html                                        <-- Hub principal actualizado (8 módulos)
├── README.md                                         <-- Documentación del repositorio
└── modulos/                                          <-- Carpeta de herramientas operativas
    ├── calculadora_hcfm.html                         <-- Calculadora HCFM y Prob. Ignición
    ├── boletin_meteorologico.html                     <-- Boletín y Pronóstico Meteorológico
    ├── mensaje_condiciones_met.html                  <-- Generador de Alertas WhatsApp
    ├── prev_meteorologia.html                        <-- Previsión Meteorológica IF
    ├── calculo_vel_propagacion.html                  <-- Cálculo de Velocidad de Propagación
    ├── visor_infraestructura_critica_valparaiso.html <-- Visor de Infraestructura Crítica
    ├── prevision_meteorologica_auto.html             <-- [EN PRUEBA] Previsión Meteorológica Automática
    └── generador_infografia_meteo.html               <-- [NEW] Generador de Infografía Meteorológica IF
```

## Características del Hub

* **Organización Personalizable (Drag & Drop):** Arrastra y suelta cualquier tarjeta para reordenar las herramientas a tu gusto. El orden se guarda automáticamente en el navegador local de cada equipo.
* **Personalización Visual:** Cada tarjeta permite editar su título, descripción y color de acento/borde mediante el botón de paleta de colores, conservando los cambios por computador.
* **Vista Previa Integrada y Apertura Directa:** Previsualiza cualquier módulo sin salir del Hub o haz doble clic sobre la tarjeta para abrirlo en una pestaña independiente.
* **Modo Claro / Oscuro:** Adaptable a condiciones de oficina o despacho nocturno.

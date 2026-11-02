# UAPIF Hub - Región de Valparaíso (CONAF)

Directorio centralizado de herramientas interactivas HTML para el análisis y predicción de incendios forestales de la Corporación Nacional Forestal (CONAF).

## Estructura del Repositorio

```text
uapif-hub/
├── index.html                                        <-- El Hub principal (Catálogo interactivo)
├── README.md                                         <-- Instrucciones de despliegue
└── modulos/                                          <-- Subcarpeta con todas las herramientas
    ├── calculadora_hcfm.html                         <-- Calculadora oficial HCFM y Prob. Ignición
    ├── boletin_meteorologico.html                     <-- Boletín y pronóstico a 3/4 días
    ├── mensaje_condiciones_met.html                  <-- Generador de Alertas WhatsApp
    ├── calculo_vel_propagacion.html                  <-- Regla de velocidad de propagación y KMZ
    └── visor_infraestructura_critica_valparaiso.html <-- Visor GIS territorial y buffer
```

## Publicación en GitHub Pages (en 2 minutos)

1. En tu repositorio de GitHub, haz clic en **Add file** > **Upload files**.
2. Arrastra `index.html` y la carpeta `modulos/` completa.
3. Haz clic en **Commit changes**.
4. Ve a **Settings** > **Pages** > En **Branch** selecciona `main` (o `master`) y carpeta `/(root)`. Presiona **Save**.
5. ¡Listo! En 1 minuto tendrás tu enlace activo funcionando en cualquier navegador:
   `https://tu-usuario.github.io/uapif-hub/`

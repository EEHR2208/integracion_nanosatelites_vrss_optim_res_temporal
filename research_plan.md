**PARTE 1: ESTRUCTURA JSON**
```json
{
  "titulo": "Integración de Redes de Nanosatélites como Sistema Complementario a la Plataforma VRSS: Optimización de la Resolución Temporal y Continuidad de Datos",
  "folder_name": "integracion_nanosatelites_vrss_optim_res_temporal",
  "abstract_preliminar": "Las plataformas de observación terrestre como el Sistema Venezolano de Satélites Remotos (VRSS) proporcionan datos de alta resolución espacial pero con limitaciones en revisita temporal. Este artículo propone la integración de una red de nanosatélites (CubeSats) como sistema complementario para mejorar la resolución temporal y asegurar la continuidad de datos en aplicaciones de monitoreo ambiental, agrícola y de desastres. Se presenta una arquitectura híbrida que combina las capacidades de los satélites VRSS-1/VRSS-2 con constelaciones de nanosatélites en órbitas LEO optimizadas. Mediante modelado orbital, simulaciones de cobertura y algoritmos de fusión de datos multi-sensor, se optimiza la frecuencia de observación y la integridad temporal. Los resultados de simulaciones muestran mejoras significativas en la revisita (de días a horas) manteniendo resoluciones espaciales compatibles. Se discuten aspectos de interoperabilidad, procesamiento en borde y validación con datos reales. Esta aproximación ofrece una solución costo-efectiva y escalable alineada con estándares IEEE para sistemas satelitales distribuidos.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el contexto de la plataforma VRSS y sus limitaciones temporales", "Motivar la necesidad de complementariedad con nanosatélites", "Definir objetivos generales y alcance del estudio"],
      "subsecciones": ["1.1 Antecedentes del programa espacial venezolano", "1.2 Limitaciones de resolución temporal en EO", "1.3 Contribuciones del trabajo"],
      "insumos": ["Figura 1: Arquitectura VRSS", "Tabla 1: Especificaciones VRSS"],
      "llaves_bibtex": ["VRSS1_2012", "Nagel2020", "Kerrouche2023"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte en Constelaciones de Nanosatélites",
      "objetivos": ["Revisar constelaciones existentes para EO", "Analizar métricas de resolución temporal y continuidad"],
      "subsecciones": ["2.1 Constelaciones comerciales (Planet, etc.)", "2.2 Aplicaciones en monitoreo dinámico", "2.3 Brechas en integración con satélites grandes"],
      "insumos": ["Tabla 2: Comparación de constelaciones"],
      "llaves_bibtex": ["BussyVirat2018", "Bouzoukis2025", "Chan2024"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Arquitectura del Sistema Híbrido Propuesto",
      "objetivos": ["Definir la topología de la red de nanosatélites", "Especificar interfaces con VRSS"],
      "subsecciones": ["3.1 Diseño orbital", "3.2 Subsistemas de nanosatélites", "3.3 Protocolos de comunicación y datos"],
      "insumos": ["Figura 2: Topología híbrida", "Eq. 1: Parámetros orbitales"],
      "llaves_bibtex": ["Kerrouche2023", "arxiv250301756"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Modelado y Optimización de Integración",
      "objetivos": ["Desarrollar modelos de cobertura y fusión", "Optimizar parámetros para continuidad"],
      "subsecciones": ["4.1 Modelos de resolución temporal", "4.2 Algoritmos de optimización multi-objetivo", "4.3 Fusión de datos multi-resolución"],
      "insumos": ["Eq. 2: Función de cobertura", "Tabla 3: Escenarios de simulación"],
      "llaves_bibtex": ["BussyVirat2018", "Chan2024"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Simulaciones y Resultados",
      "objetivos": ["Evaluar desempeño mediante simulación", "Comparar métricas antes/después de integración"],
      "subsecciones": ["5.1 Configuración experimental", "5.2 Análisis de cobertura y latencia", "5.3 Validación con datos de caso"],
      "insumos": ["Figura 3: Mapas de cobertura", "Tabla 4: Métricas cuantitativas"],
      "llaves_bibtex": ["Bouzoukis2025", "arxiv250301756"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados", "Analizar limitaciones y viabilidad"],
      "subsecciones": ["6.1 Implicaciones operativas", "6.2 Aspectos económicos y de implementación", "6.3 Comparación con enfoques alternativos"],
      "insumos": [],
      "llaves_bibtex": ["Nagel2020", "Kerrouche2023"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos", "Proponer direcciones futuras"],
      "subsecciones": ["7.1 Conclusiones principales", "7.2 Recomendaciones", "7.3 Trabajos futuros"],
      "insumos": [],
      "llaves_bibtex": ["Chan2024", "VRSS1_2012"]
    }
  ]
}
```

**PARTE 2: BLOQUES BIBLIOGRÁFICOS SECCIONALES**

```bibtex
@misc{VRSS1_2012,
  author    = {Agencia Bolivariana para Actividades Espaciales},
  title     = {VRSS-1 (Francisco de Miranda) - Venezuelan Remote Sensing Satellite},
  year      = {2012},
  url       = {https://en.wikipedia.org/wiki/VRSS-1},
  note      = {Accessed: 2026}
}
```

```bibtex
@article{Nagel2020,
  author    = {Nagel, G. W. and others},
  title     = {Nanosatellites applied to optical Earth observation: a review},
  journal   = {Ámbio Água},
  year      = {2020},
  volume    = {15},
  number    = {2},
  doi       = {10.4136/ambi-agua.2228},
  url       = {https://www.scielo.br/j/ambiagua/a/N6LwG3sVTq96RzQFhdgLFXD/?lang=en},
  note      = {[Online]. Available: https://www.scielo.br/j/ambiagua/a/N6LwG3sVTq96RzQFhdgLFXD/}
}
```

```bibtex
@article{Kerrouche2023,
  author    = {Kerrouche, K. D. E. and others},
  title     = {Applications of Nanosatellites in Constellation},
  journal   = {Sensors},
  volume    = {23},
  number    = {13},
  year      = {2023},
  doi       = {10.3390/s23136232},
  url       = {https://www.mdpi.com/1424-8220/23/13/6232},
  note      = {[Online]. Available: https://www.mdpi.com/1424-8220/23/13/6232}
}
```

```bibtex
@article{BussyVirat2018,
  author    = {Bussy-Virat, C. D. and Ruf, C. S. and Ridley, A. J.},
  title     = {Relationship between temporal and spatial resolution for a constellation of GNSS-R satellites},
  journal   = {IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  year      = {2018},
  url       = {https://cygnss.engin.umich.edu/wp-content/uploads/sites/534/2021/06/JSTARS-2018_Bussy-Virat_etal_GNSS-R_Spatial-Temporal-Res.pdf},
  note      = {PDF available}
}
```

```bibtex
@article{Bouzoukis2025,
  author    = {Bouzoukis, K. P. and others},
  title     = {An Overview of CubeSat Missions and Applications},
  journal   = {Aerospace},
  volume    = {12},
  number    = {6},
  year      = {2025},
  doi       = {10.3390/aerospace12060550},
  url       = {https://www.mdpi.com/2226-4310/12/6/550},
  note      = {[Online]. Available: https://www.mdpi.com/2226-4310/12/6/550}
}
```

```bibtex
@misc{Chan2024,
  author    = {Chan, M.},
  title     = {Toward Real-time Earth Observation with Satellite Constellation Crosslinks and Propulsion},
  year      = {2024},
  url       = {https://dspace.mit.edu/handle/1721.1/154033},
  note      = {MIT Thesis. [Online]. Available: https://dspace.mit.edu/handle/1721.1/154033}
}
```

```bibtex
@misc{arxiv250301756,
  author    = {Authors et al.},
  title     = {Nanosatellite Constellation and Ground Station Co-design for Low-Latency Critical Event Detection},
  year      = {2025},
  url       = {https://arxiv.org/html/2503.01756v1},
  note      = {arXiv preprint. [Online]. Available: https://arxiv.org/html/2503.01756v1}
}
```

**PARTE 3: MAPA DE USO DE REFERENCIAS (POR SECCIÓN)**

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "VRSS1_2012": {
      "razon_seleccion": "Fuente primaria sobre especificaciones y capacidades de la plataforma VRSS.",
      "guia_redaccion": "Usar en 1.1 para describir características técnicas de VRSS-1/2 y motivar limitaciones temporales.",
      "subseccion_destino": "1.1"
    },
    "Nagel2020": {
      "razon_seleccion": "Revisión clave sobre nanosatélites en observación óptica de la Tierra.",
      "guia_redaccion": "Citar en 1.2-1.3 para resaltar ventajas en resolución temporal de constelaciones.",
      "subseccion_destino": "1.2"
    },
    "Kerrouche2023": {
      "razon_seleccion": "Ejemplos de aplicaciones de constelaciones de nanosatélites.",
      "guia_redaccion": "Usar en introducción para contextualizar eficiencia en EO y monitoreo.",
      "subseccion_destino": "1.3"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte en Constelaciones de Nanosatélites",
  "mapa_uso": {
    "BussyVirat2018": {
      "razon_seleccion": "Análisis cuantitativo de trade-off temporal-espacial en constelaciones.",
      "guia_redaccion": "Citar en 2.1-2.2 para discutir relación entre resoluciones y diseño de constelaciones.",
      "subseccion_destino": "2.1"
    },
    "Bouzoukis2025": {
      "razon_seleccion": "Revisión actualizada de misiones CubeSat y aplicaciones EO.",
      "guia_redaccion": "Usar en tabla comparativa y para ejemplos de constelaciones recientes.",
      "subseccion_destino": "2.2"
    },
    "Chan2024": {
      "razon_seleccion": "Enfoque en observación en tiempo real mediante crosslinks y propulsión.",
      "guia_redaccion": "Integrar en 2.3 para destacar brechas y oportunidades de integración.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Arquitectura del Sistema Híbrido Propuesto",
  "mapa_uso": {
    "Kerrouche2023": {
      "razon_seleccion": "Proporciona ejemplos prácticos de aplicaciones en constelación.",
      "guia_redaccion": "Usar para justificar elección de subsistemas y topología.",
      "subseccion_destino": "3.2"
    },
    "arxiv250301756": {
      "razon_seleccion": "Co-diseño de constelación y estaciones terrestres para baja latencia.",
      "guia_redaccion": "Citar en diseño orbital y protocolos para optimizar continuidad.",
      "subseccion_destino": "3.1"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Modelado y Optimización de Integración",
  "mapa_uso": {
    "BussyVirat2018": {
      "razon_seleccion": "Modelo de relación temporal-espacial fundamental para optimización.",
      "guia_redaccion": "Base para Eq. de cobertura y algoritmos multi-objetivo.",
      "subseccion_destino": "4.1"
    },
    "Chan2024": {
      "razon_seleccion": "Técnicas avanzadas para entrega rápida de datos en constelaciones.",
      "guia_redaccion": "Integrar en fusión de datos y optimización de latencia.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Simulaciones y Resultados",
  "mapa_uso": {
    "Bouzoukis2025": {
      "razon_seleccion": "Métricas de rendimiento de CubeSats en EO.",
      "guia_redaccion": "Comparar resultados de simulación con benchmarks de constelaciones reales.",
      "subseccion_destino": "5.2"
    },
    "arxiv250301756": {
      "razon_seleccion": "Simulaciones de cobertura y detección de eventos.",
      "guia_redaccion": "Usar metodología para validar mejoras en continuidad.",
      "subseccion_destino": "5.1"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "Nagel2020": {
      "razon_seleccion": "Tendencias y limitaciones de nanosatélites en EO.",
      "guia_redaccion": "Discutir viabilidad económica y técnica de la integración propuesta.",
      "subseccion_destino": "6.2"
    },
    "Kerrouche2023": {
      "razon_seleccion": "Eficiencia demostrada en aplicaciones reales.",
      "guia_redaccion": "Contrastar con limitaciones de VRSS y beneficios híbridos.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Chan2024": {
      "razon_seleccion": "Perspectivas hacia observación en tiempo real.",
      "guia_redaccion": "Proponer extensiones con crosslinks y propulsión en trabajos futuros.",
      "subseccion_destino": "7.3"
    },
    "VRSS1_2012": {
      "razon_seleccion": "Cierre contextual con plataforma base.",
      "guia_redaccion": "Comparar logros propuestos con capacidades actuales de VRSS.",
      "subseccion_destino": "7.1"
    }
  }
}
```
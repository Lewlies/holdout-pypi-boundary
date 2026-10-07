# holdout-pypi-boundary

Repositorio sintético del conjunto de reserva (*hold-out*) del TFG *Análisis automatizado de vulnerabilidades en dependencias de software*. No contiene código, solo el manifiesto de dependencias.

No se usó para diseñar sca-gate. El ground truth (`ground_truth.yaml`) se escribió antes de ejecutar la herramienta sobre él.

| Dimensión | Paquete | Identificador |
|---|---|---|
| borde, lado vulnerable (0.4.3, corregido en 0.4.4) | sqlparse | CVE-2023-30608 |
| aviso retirado por duplicado de GHSA-2m57-hf25-phgg | sqlparse | GHSA-62qf-jcq8-8gxw |
| borde, lado corregido (primera version sin CVE-2022-29217) | pyjwt 2.4.0 | CVE-2022-29217 |

# ParkLab República Dominicana

Una comunidad abierta de datos, ciencia y áreas protegidas en la República Dominicana.

Sitio web: https://parklabdr.org/

## Cómo actualizar el sitio

Todo el contenido (talleres, fotos, personas y socios) está en el bloque `<script id="site-data">` al inicio de `index.html`. Cada texto tiene una versión en español (`es`) y en coreano (`ko`).

## 사이트 수정 방법

모든 내용(워크숍, 사진, 사람, 협력기관)은 `index.html` 앞부분의 `<script id="site-data">` 블록에 있습니다. 각 문장은 스페인어(`es`)와 한국어(`ko`)로 되어 있습니다.


## Enlaces a los materiales / 교육자료 링크 규칙

- ID de cada capacitación / 연수 ID: `cap-AÑO-N` (N = número acumulado de la Capacitación en el Uso de Datos / 연수 누적 회차). Ej. `cap-2025-3`, `cap-2026-4`.
- Dirección / 주소: `https://parklabdr.org/#materiales/<ID>`
  - `#materiales/<ID>/preparacion`: QGIS y datos / 설치와 데이터
  - `#materiales/<ID>/guias`: guías de los talleres / 실습 교안
- Para publicar materiales de una capacitación, agregue `downloads` o `parts[].pdf` a su entrada en `site-data`; aparecerá sola en la página Materiales. / 연수 항목에 `downloads` 또는 `parts[].pdf`를 넣으면 교육자료 페이지에 자동으로 나타납니다.
- Archivos en GitHub Releases: use el ID como etiqueta (`cap-2025-3`). La etiqueta `taller-2026-11` se mantiene para no romper enlaces. / 릴리스 태그는 연수 ID와 같게. 기존 `taller-2026-11` 태그는 링크 보존을 위해 유지
- `#descargas` (enlace antiguo, ya compartido) lleva a los materiales más recientes. / 예전 링크 `#descargas`는 최신 연수 자료로 이동

---

En el marco del Proyecto de Fortalecimiento del Monitoreo del Cambio Climático en Parques Nacionales basado en TIC (KOICA y MMARN), ejecutado por el Servicio de Parques Nacionales de Corea (KNPS).

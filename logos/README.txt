OPTIONAL — REAL COMPANY / SCHOOL LOGOS
======================================

By default each experience/education entry shows a clean monogram (ON, OC, DE, EN, ES...).
That already looks professional and never breaks.

If you want the ACTUAL logo instead, drop a square PNG (transparent background is best)
in THIS folder with these EXACT names:

  oncf.png        (Groupe ONCF)
  decathlon.png   (Decathlon)
  admitease.png   (AdmitEase)
  ocp.png         (OCP Group)
  esith.png       (ESITH)         <- used for both the ESITH job and the ESITH diploma
  ensait.png      (ENSAIT)
  cpge.png        (your prépa, optional)

Rules:
- PNG, lowercase name, exactly as above. Square-ish (e.g. 128x128 or 256x256).
- Transparent background looks cleanest on the dark theme.
- If a file is missing, the monogram is shown instead. Nothing breaks.

Where to get them: the school/company official website (right-click their logo > save),
or a "brand logo png" search. Then rebuild:  npm run build  &&  bash deploy.sh

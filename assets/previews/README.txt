Optional: system screenshots for the "click a planet → preview" feature
=========================================================================

When you click a system on the orbit, it now tries to load a screenshot
from this folder. If the file isn't there yet, it falls back automatically
to the old text-only detail card — so the site works fine with zero images
here. Add these whenever you get a chance, one system at a time.

FILENAMES (must match exactly — lowercase, .webp):

  lrhub.webp        Learning Resource Hub
  enroll.webp       SMART SANHS Enrollment
  depthead.webp     Dept Heads Monitoring
  teacherhub.webp   TeacherHub PH
  ilaw.webp         ILAW LP Generator
  mtmon.webp        MT Monitoring
  explainhub.webp   ExplainHub
  tos.webp          TOS AI Generator
  smartpass.webp    SANHS SMART Pass
  quizcade.webp     Quizcade
  sped.webp         SPED Data Consolidation System
  cluster1.webp     Cluster 1 School Performance M&E
  ilead.webp        ILEAD CPD Program Management System

SPECS

  - Format: WebP
  - Size: ~1200x700px (or any 12:10-ish landscape crop) — the preview
    card crops to a 12:7 box, so keep the important part of the UI
    centered/top of the frame.
  - File size: aim for under ~120KB each so the previews stay snappy.
  - Content: the first meaningful screen of the app — a dashboard, a
    login/hero screen, or the main working view. Not a deep sub-page.

HOW TO CAPTURE

  1. Open the live app at a normal desktop width (~1440px).
  2. Take a screenshot of just the browser viewport (not the full page).
  3. Crop to roughly 12:7 (a bit wider than tall).
  4. Convert to WebP (squoosh.app is a free, no-install option) and
     compress until it's under ~120KB without looking blurry.
  5. Save it here with the exact filename above.

That's it — no code changes needed. The site checks for the file, and
uses it the moment it's present.

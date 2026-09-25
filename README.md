
<img width="512" height="512" alt="Firefly_fais moi un logo d&#39;application sur fond uni DeskHandCtrl, pas de Français ou texte, q 299454" src="https://github.com/user-attachments/assets/fe196410-b153-4643-8ea5-28f39832d038" />

Convertissor - version portable
================================

Ce dossier est autonome : copiez-le tel quel sur une clé USB ou un autre
disque et lancez Convertissor.exe.

Application en plusieurs langues EN FR DE ES IT PT RU

Contenu
-------
Convertissor.exe      application en rust (interface graphique)
ffmpeg / ffprobe /
ffplay.exe            conversion et lecture audio/vidéo
yt-dlp.exe            téléchargement depuis une URL
tesseract.exe + *.dll moteur OCR (Tesseract 5.4.0)
tessdata\             données de reconnaissance (anglais inclus)


Conversions disponibles
-----------------------
Images / Photos  -> PDF, ICO, JPG, PNG, WEBP, BMP, TIFF
Textes           -> PDF (txt, md, csv, xls, xlsx, ods, docx, doc, rtf, odt)
Audio            -> MP3, FLAC, AAC, WAV, OGG, M4A (+ URL)
Vidéo            -> MP4, AVI (+ URL)
OCR              -> TXT ou PDF (texte recherchable)

Notes
-----
* OCR : les langues autres que l'anglais (français, allemand, espagnol,
  italien, portugais, russe, chinois, japonais, coréen) sont téléchargées
  automatiquement à la première utilisation (~1 à 4 Mo chacune) puis
  conservées dans le dossier tessdata de ce dossier portable.

* Documents .doc, .rtf, .odt : la conversion passe par LibreOffice, qui
  doit être installé sur le poste (gratuit et libre :
  https://www.libreoffice.org/download/). Il n'est pas inclus ici car il
  pèse plusieurs centaines de Mo. Les .docx fonctionnent aussi sans
  LibreOffice (extraction du texte seule).

* Les formats .docx/.xlsx/etc. sont lus nativement, aucune installation
  supplémentaire n'est nécessaire.

Aucune installation, aucune inscription dans le registre.

English : 

This folder is self-contained: copy it as-is to a USB drive or another disk and run Convertissor.exe.

Contents
Convertissor.exe: Rust-based application (GUI) | ffmpeg / ffprobe / ffplay.exe: audio/video conversion and playback | yt-dlp.exe: download from URL | tesseract.exe + *.dll: OCR engine (Tesseract 5.4.0) | tessdata\: recognition data (English included)

Available conversions
Images/Photos -> PDF, ICO, JPG, PNG, WEBP, BMP, TIFF | Text -> PDF (txt, md, csv, xls, xlsx, ods, docx, doc, rtf, odt) | Audio -> MP3, FLAC, AAC, WAV, OGG, M4A (+ URL) | Video -> MP4, AVI (+ URL) | OCR -> TXT or PDF (searchable text)

Notes
OCR: languages ​​other than English (French, German, Spanish, Italian, Portuguese, Russian, Chinese, Japanese, Korean) are automatically downloaded upon first use (~1 to 4 MB each) and stored in the `tessdata` folder within this portable directory.

.doc, .rtf, .odt documents: conversion relies on LibreOffice, which must be installed on the system (free and open-source: https://www.libreoffice.org/download/). It is not included here due to its large size (several hundred MB). .docx files work without LibreOffice (text extraction only).

.docx/.xlsx/etc. formats are read natively; no additional installation is required.

No installation, no registry entries.

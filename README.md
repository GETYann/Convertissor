
<img width="512" height="512" alt="Firefly_fais moi un logo d&#39;application sur fond uni DeskHandCtrl, pas de Français ou texte, q 299454" src="https://github.com/user-attachments/assets/fe196410-b153-4643-8ea5-28f39832d038" />

Convertissor - version portable
================================

Ce dossier est autonome : copiez-le tel quel sur une clé USB ou un autre
disque et lancez Convertissor.exe.

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

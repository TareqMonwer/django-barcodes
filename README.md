# django-barcodes
Create barcodes, barcode images, barcode template-tags, templates, pdfs, stickers etc.


## Library Goals/Plans:
+ Create barcode for selected models from abstract BarcdeBaseModel.
+ Choose barcode sticker layouts, select fields from BarcodeBaseModel's child models.
+ Generate barcode images in specified location.
+ BarcodePrintView, BarcodeRenderView to render barcodes as PDF or HTML.
+ Ensure utf-8 encoding support in PDF's.
+ Make generic pdf renderer using either weasyprint or xhtml2pdf.
+ Define barcode generate template/pdf layouts/sizes.

# Merge pdfs using PyPdf2 module
Are you having trubles to pay to merge pdfs.Now you will not have this problem you can merge them for free and whats more that you will do it yourselves:

Use this code:
```python
from PyPDF2 import PdfWriter

merger = PdfWriter()

for pdf in ["file1.pdf", "file2.pdf", "file3.pdf"]:
    merger.append(pdf)

merger.write("merged-pdf-2.pdf")
merger.close()

``` 
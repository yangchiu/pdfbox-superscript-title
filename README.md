# Tag Superscripts and Titles in a Journal Paper PDF File with PDFBox
- Based on Apache PDFBox, extends PDFTextStripper class

- If the Y-scale of a word is smaller than the average size, it would be regarded as a superscript.
- If the Y-scale of a word is larger than the average size, it would be regarded as a title. 

- If a superscript found in the document, it would be tagged as \<sup>superscript\</sup>
- If a title found in the document, it would be tagged as <title>title</title> 

#### Dependency
* Apache PDFBox

#### Usage
Java:
```python
$java -jar pdfbox_sup_title.jar your_pdf_file
```
Python:
```python
$python pdfbox_sup_title.py your_pdf_file
```

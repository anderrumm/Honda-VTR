2000 Firestorm manual part number is  something like 62MBB00Y, change the last letter for the year.

This manual was online and is:
VTR1000F Honda Service Manual OCR.pdf

cpdf commands to split file into maileable chunks.
command contains page numbers file comtains and file name chapters contained in file.

./cpdf VTR*.pdf 1-95 -o vtr-manual1-5.pdf
./cpdf VTR*.pdf 96-149 -o vtr-manual6-8.pdf
./cpdf VTR*.pdf 150-206 -o vtr-manual9-12.pdf
./cpdf VTR*.pdf 207-280 -o vtr-manual13-15.pdf
./cpdf VTR*.pdf 281-404 -o vtr-manual16-24.pdf



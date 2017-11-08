# PDF_ABCPDF_GetTextFromPDF
ABCPDF(WebSuperGoo) Version 10

ABCPDF_GetTextFromPDF

- Version 10

- Extract Text from Flattened PDF file with X:Y position
  //250 500 400 520 --> X:250, Y:500, Width:400-250=150, Height:520-500=20 
  int pageNumber = 1; 
  XRect rect = new XRect(txtExtractRect.Text); 
  txtExtracted.Text = op.GetText(rect, pageNumber);

- Direct Convert from PDF to multipaged TIFF

- Form Field Editing and Flattend(Stamp)

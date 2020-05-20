# Aspose DOC TO PDF TO XML TO HTML


  ## Document to PDF:

            public class test
            {
            public static void main(String args[]) throws Exception{

            Doument doc = new Document("X:\\W TUTORIALS\\DOCUMENT\\DOCUMENT.doc");

            doc.save("X:\\W TUTORIALS\\DOCUMENT\\pdfDOCUMENT.pdf");
            
            doc.save("X:\\W TUTORIALS\\DOCUMENT\\pdfDOCUMENT.pdf",SaveFormat.TEXT);

            }

            }
            
            
### To Render only a first Page:

           public class test
                {
                public static void main(String args[]) throws Exception{

                Doument doc = new Document("X:\\W TUTORIALS\\DOCUMENT\\DOCUMENT.doc");

                PdfSaveOptions saveoptions = new PdfSaveOptions();

                saveoptions.setPageIndex(0);   // defines the first page to start savings

                saveoptions.setPageCount(1);   //saves only first page

                doc.save("X:\\W TUTORIALS\\DOCUMENT\\pdfDOCUMENT.pdf");

                doc.save("X:\\W TUTORIALS\\DOCUMENT\\pdfDOCUMENT.pdf",SaveFormat.TEXT);

                }

                }
                
## Document to PDF,TXT:

        Document doc = new Document("F:\\starwalt\\ava aspose jars\\tt.doc");

          doc.save("F:\\starwalt\\ava aspose jars\\testydf.pdf");

          doc.save("F:\\starwalt\\ava aspose jars\\tt.txt", SaveFormat.TEXT);

            
 ## SaveFormat :
 
                DOC
                DOM
                DOCX
                DOT
                DOTM
                DOTX
                EPUB
                FLAT_OPC
                HTML
                MHTML
                OTT
                RTF
                PDF
                TEXT
                WORD_ML
                XAML_FIXED
  

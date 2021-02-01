This is a brief guideline for finding your desired spectra from this downloadable RELAB database.

1. Download Sample_Catalogue and Spectra_Catalogue under the catalogues/ folder.

2. In Sample_Catalogue, find Sample IDs for your desired samples.  Then, search for that Sample ID in Spectra_Catalogue to find the spectral file names.  Sample photos are also available if any.

3. Go into data/ folder to find the files.  The data/ folder is structured according to three-letter PI code and first two letters of Sample ID.

For example, if you find your desired sample has "LS-CMP-012" in Sample_Catalogue,
identify the file names such as C1LS12 in Spectra_Catalogue, go to data/cmp/ls/ folder,
and find c1ls12.asc, c1ls12.txt, etc.

There are two files for the same spectral data: .asc and .txt formats.

<ASC format>
  1st line   :  Number of data points
  2nd line - :  Wavelength (nm), Reflectance, and Standard deviation (if available)
                (delimited with spaces)
  Last lines :  File name and comments

<TXT format>
  1st line   :  Sample ID and file name
  2nd line   :  Data column headers
  3rd line - :  Wavelength (micron), Reflectance, and Standard deviation (if availabe)
                (delimited with tabs)

See Catalogue_README.html file to learn about other columns in Sample_Catalogue.

Alternatively, you can download a compressed zip file containing all the catalogues and data placed here.

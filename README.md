# PSIDfilesStata
Reads ASCII data (family and individual) files and saves in '.dta' format.

The STATA file 'create_dta.do' converts the PSID data (family and individual files) from ASCII (.txt) into STATA (.dta) format. It does so year-by-year for the family files and once for the cross-year individual file. In doing do it reads accompanying STATA code that relies on the PSID-provided STATA statements. Period covered: 1968-2013. 

To run 'create_dta.do' one needs access to the annual PSID family files (http://simba.isr.umich.edu/VS/f.aspx) and the cross-year individual file (http://simba.isr.umich.edu/Zips/ZipMain.aspx).

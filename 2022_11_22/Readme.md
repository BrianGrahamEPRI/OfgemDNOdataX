Short description of the provided application profiles

The application profiles are provided to facilitate the implementation of the CGMES profiles and related constraints as defined in IEC 61970-600-1:2021, IEC 61970-600-2:2021, IEC 61970-301 and other related 61970-45x series of profiles. The application profiles are packaged in the following folders:

•	RDFS2020
o	An improved export of the RDFS augmented version that is based on IEC 61970-501:2006 (Ed1) and used for exporting the RDFS for CGMES v2.4. The only difference is resolving export technical issues and the information from the abstract version class that is now instantiated as part of the header of the RDFS. No functional changes. 2020 does not refer to the year of generation, but it is the version of the augmented RDFS export by CimSyntaxGen.

•	RDFSEd2Beta
o	This is a beta version of RDFS according to the draft IEC 61970-501:Ed2. Please use these files for information on the direction where RDFS will evolve in that standard. Namely the RDFS contains the vocabulary and the constraints (cardinalities, datatypes, etc.) are expressed by SHACL.

•	SHACL
o	This is a package of all SHACL shapes/constraints applicable for CGMES v3.0. These are constraints for cardinalities and datatypes derived from the RDFS, constraints defined in the descriptions of the classes and attributes, constraints defined in IEC 61970-600-1:2021, IEC 61970-600-2:2021, IEC 61970-301 and other related 61970-45x series of profiles and expressed there in plain English text. Note that SHACL based constraints in this folder are serialized in two RDF formats, TURTLE and RDF XML plain (no nesting). Originally the constraints were developed in TURTLE and then converted to RDF XML. Because many constraints rely on SHACL SPARQL method, which is not covered in the draft IEC 61970-501:Ed2, the RDF XML may not represent the desired way of serialization the RDF XML version should be used with a caution.  

•	OCL
o	This is a package of OCL based constraints that cover CGMES v3.0 in a similar way as SHACL shapes cover this. The RDFS Extracted folder contains OCL constraints derived from the RDFS. The XLSX Extracted folder contains constraints defined in the descriptions of the classes and attributes, constraints defined in IEC 61970-600-1:2021, IEC 61970-600-2:2021, IEC 61970-301 and other related 61970-45x series of profiles and expressed there in plain English text. However, please note that this package was developed in Nov 2020 and may have deviations compared to the published version of CGMES v3.0.

Disclaimer
The test configurations (models), documents and application profiles are owned by ENTSO-E and are provided by ENTSO-E “as it is”. To the fullest extent permitted by law, ENTSO-E shall not be liable for any damages of any kind arising out of the use of the test configurations (models), documents and application profiles (including any of their subsequent modifications).
ENTSO-E neither warrants, nor represents that the use of the test configurations (models), documents and application profiles will not infringe the rights of third parties. Any use of the test configurations (models), documents and application profiles shall include a reference to ENTSO-E. ENTSO-E web site is the only official source of information related to these test configurations (models), documents and application profiles.

# Fields of Science

## Files and Links

* [nsf_fos.pdf](../nsf_fos.pdf) - NSF Fields of Science
* [SED Field of Science Taxonomy Changes](https://ncses.nsf.gov/pubs/ncses23200#changes-in-the-field-of-study-taxonomy-and-education-data-collection_new-cip-based-field-of-study-taxonomy)
* [SED-CIP 2021 System](./nsf24300-taba-005.xlsx)
* [CIP Codes](https://nces.ed.gov/ipeds/cipcode/browse.aspx?y=55)


## Current State of OSG Fields of Sciences

The current Fields of Science used for Topology are loosely based on the 2010 CIP (Classification of Instructional Programs)
and SED (Survey of Earned Doctorates) Codes from this [document](../nsf_fos.pdf).

Fields of Science are taken from the project files in Topology and mapped with a 
[mapping file](https://github.com/opensciencegrid/topology/blob/5248f5e2322f711b28ce767a0348564e65907aec/mappings/nsfscience.yaml). 

The mapping file on Topology maps the NSF fields from the yaml to a NSF defined Field of Science. 
These NSF Fields of Science originate in this [pdf](../nsf_fos.pdf). The mapping file is not strict
in its adherence to this PDF and has additional fields and casing inconsistencies.

## Current State of NSF Fields of Science

NSF does a annual survey of earned doctorates (SED) and recently (2021) updated their list of Fields of Science.

The new [classification system](https://ncses.nsf.gov/pubs/ncses23200#changes-in-the-field-of-study-taxonomy-and-education-data-collection_new-cip-based-field-of-study-taxonomy) is CIP based with some additions and omissions.

The new row level classification can be found [here](./nsf24300-taba-005.xlsx)

## Potential Future

### Fix the existing Fields of Science using the old Doc

Fix the existing Fields of Science as shown in my [PR](https://github.com/opensciencegrid/topology/pull/3500). 

This standardizes the values and casing to adhere to the original NSF Fields of Science PDF.

### Add a new entry for the new NSF Fields of Science

Have all new projects also provide a value that adheres to the updated SED-CIP list. 

This way we can start the transition process to a better standard, have easy migration paths as new FOS are released, and 
can provide more granular information on a projects field of science.

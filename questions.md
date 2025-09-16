# RDM Lifecycle Questions

## plan - Plan
- [yes] Should a Data Management Plan (DMP) be started before data collection begins? :: A DMP guides consent, formats, storage, and sharing decisions from day one.
- [no] Is choosing file formats only a concern after analysis is complete? :: Sustainable, open formats should be chosen up front to avoid costly migrations.
- [yes] Do funders often require a DMP at proposal stage? :: Many funders mandate a DMP with the grant application.

## collect - Collect
- [yes] Should you record metadata as you collect data (not afterwards)? :: Real-time metadata avoids loss of context and improves reproducibility.
- [no] Is it okay to skip consent documentation if data look anonymous? :: Ethics and legal compliance require documented consent when applicable.
- [yes] Are controlled vocabularies helpful when naming variables? :: Shared vocabularies make data interoperable and easier to reuse.

## process - Process
- [yes] Should you keep raw data immutable and process copies? :: Raw data are the ground truth; processing should be reproducible on copies.
- [no] Is it fine to do manual changes without logging them? :: Every transformation must be tracked for provenance and auditability.
- [yes] Can workflow automation help reduce errors in processing? :: Pipelines and scripts reduce human error and improve repeatability.

## analyse - Analyse
- [yes] Should analysis environments (versions, seeds) be documented? :: Documented environments enable others to reproduce figures and results.
- [no] Is p-hacking an acceptable way to find significant results? :: Selective reporting biases conclusions and violates good scientific practice.
- [yes] Is it good practice to link analysis code to the dataset it uses? :: Tight linkage improves transparency and reproducibility.

## preserve - Preserve
- [yes] Does long-term preservation require more than local lab storage? :: Repositories and institutional storage provide durability and stewardship.
- [no] Is one backup in the same room as the originals enough? :: Follow 3-2-1: 3 copies, 2 media, 1 offsite.
- [yes] Do persistent identifiers (like DOIs) help with preservation? :: PIDs ensure long-term findability and stable citation.

## share - Share & Publish
- [yes] Should you choose a license when you share your dataset? :: Licenses tell others how they can reuse your data.
- [no] Is it okay to upload sensitive data to any public repository? :: Sensitive data require controlled access and appropriate repositories.
- [yes] Do rich metadata increase discoverability when publishing? :: Good descriptions and keywords help others find your dataset.

## reuse - Reuse
- [yes] Should you cite datasets you reuse, like you cite papers? :: Proper citation credits creators and tracks impact.
- [no] If metadata are unclear, should you ignore restrictions? :: Always respect licensing and access terms; clarify before use.
- [yes] Is reusability improved by open formats and clear provenance? :: Open formats + provenance enable integration and verification.

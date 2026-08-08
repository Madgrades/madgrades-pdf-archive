# uw-madison-pdf-archive

An archive of publicly available UW–Madison academic PDF reports used by Madgrades and related data-processing projects.

This repository stores source documents only. Extraction, transformation, and validation logic belong in separate repositories such as [`uw-madison-pdf-extractor`](https://github.com/Madgrades/uw-madison-pdf-extractor).

## Using this data

The reports in this repository are commonly used by projects such as [Madgrades](https://madgrades.com) to help students explore historical course and grade information.

These reports should be interpreted with care. They were not necessarily designed for the purposes of external analysis, and errors can be introduced through extraction, interpretation, or differences in university terminology and reporting practices.

Grade distributions are also only one source of information when evaluating a course. Students may want to consider other sources, including instructors, other students, university resources, course descriptions, and their own academic interests and goals.

The goal of this archive is to preserve access to useful public records for informational and research purposes while encouraging responsible interpretation.

## Departmental Instructional Report (DIR) data

The University of Wisconsin–Madison has stated that it does not endorse republication of Departmental Instructional Report (DIR) data on external websites.

Although DIR reports are publicly available, they are primarily intended for internal administrative use. Their terminology, structure, and organization reflect university academic systems and business processes, and those details may need to be understood before drawing conclusions from the data.

Madgrades acknowledges this position while also recognizing the value of public access to these records for informational and research purposes.

When using DIR data:

* **Understand the context.** These reports were created for internal university purposes and may not map directly to external interpretations or use cases.
* **Interpret cautiously.** Apparent patterns in the data may depend on university-specific terminology, reporting rules, or extraction assumptions.
* **Use responsibly.** Do not use the data to harass, target, or otherwise cause harm to individuals.

## Repository contents

One PDF from each available fall and spring semester should be stored in the appropriate directory:

* `grades` contains published tabular [course grade-distribution reports](https://registrar.wisc.edu/grade-reports/) under **Course grade-distribution reports**.

  * Pre-2014 grade-distribution reports are also available [here](https://uwmadison.app.box.com/s/40rmvbsws0yzbcmb7gj2yc8ufpqvotds).
* `dir` contains published tabular [final Departmental Instructional Reports (DIR)](https://registrar.wisc.edu/curricular-build/#dir).

This repository is intended to preserve the original source PDFs rather than transformed or normalized datasets.

## Contributing

Contributions are welcome, particularly for:

* adding newly published semester reports
* filling gaps in the archive
* correcting misplaced or incorrect source files

Please submit changes through a pull request.

Changes to this repository may trigger downstream processing used by Madgrades, including extraction of the source PDFs and deployment of updated data to [Madgrades](https://madgrades.com).

An administrator will review and approve pull requests before they are merged.

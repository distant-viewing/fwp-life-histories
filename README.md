## FWP Life History Project in the American South: Machine Readable Text and Metadata

**License:** [GPL-2](https://opensource.org/licenses/GPL-2.1)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3865765.svg)](https://doi.org/10.5281/zenodo.3865765)

The data is created from documents in the Federal Writers’ Project (FWP) Papers, 1936-1940 held at The Southern
Historical Collection at the Louis Round Wilson Special Collections Library at the University of North
Carolina – Chapel Hill. From 1936-1939, writers were sent across the American South to record life
histories as a part of the Southern Life History Project. Previously only PDFs, each life history has been
transformed into a .txt file. The csv files include metadata about the life histories such as  writer name
along with their race and gender, interviewee name along with their race and gender, reviser along with race
and gender, location of the interview, and year. The data was designed for a historical research project,
so scholars made decisions about race and gender guided by their expertise on the era and the analytical
questions driving the project. It should be noted that labeling people by race and gender is a complicated
process and practice of power, so care should be taken when using these categories. The data only includes
the life histories held at UNC-CH, so it is not a complete collection of all life histories conducted in
the region. The data was created for the Photogrammar project with funding from an American Council of
Learned Societies (ACLS) Digital Extension Grant. As a condition of the funding, the data is made
available under a GNU Public License (GPL).

### Available files

Each life history is stored in a txt file, available in the directory `text`. Files are named according
to "interview_XXXX_YYY.txt" where "XXXX" refers to the archival folder number and "YYY" provides the
start page for the interview in the PDF filed (some folders contain multiple interviews).

The metadata files are stored as normalized csv files in the directory "csv". The following files are
available:

- `interview.csv` contains one row for each interview, with columns such as the date, location, and
title of the interview
- `interviewee.csv` contains one row for each listed interviewee, along with available information
such as race, age, and gender; some interviews are linked to multiple people
- `occupation.csv` contains listed occupations mentioned in each interview
- `writer.csv` contains one row for each of the writers involved with the project
- `reviser.csv` information about editor that revised the interview before it was published
- `interviewee_crosswalk.csv` links the interviews to the interviewees
- `reviser_crosswalk.csv` links the interviews to the revisers
- `writer_crosswalk.csv` links to the interviews to the writers

The original archival material is held by the Wilson Library at the University of North Carolina at Chapel
Hill. Digital versions are made available at:
[Collection Title: Federal Writers' Project Papers, 1936-1940](https://finding-aids.lib.unc.edu/03709/).

### Citation

To cite this dataset, please reference:

    Arnold, Taylor, Emeline Blevins Alexander, Courtney Rivard, Lauren Tilton,
    and Laura Wexler. (2020). "FWP Life History Project in the American South:
    Machine Readable Text and Metadata." (Version 1.0) [Data Set]. Zenodo.
    DOI: 10.5281/zenodo.3865765

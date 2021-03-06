# Minnesota

Shapefiles for election results per precincts is [downloaded](http://www.gis.leg.mn/html/download.html) from the `LCC-GIS` or Legislative Coordinating Commission - Geospatial Information in long form.

Includes results for 2008, 2010, 2012, 2014, and 2016. Downloaded 2017-03-13.

There are also downloads for state gov't districts on the same page, but those weren't downloaded.

- **2016** precincts with election results. Citation: _Florida Election Science Team, 2018, "2016 Precinct-Level Election Results", [https://doi.org/10.7910/DVN/NH5S2I](https://doi.org/10.7910/DVN/NH5S2I), Harvard Dataverse, V2._
  - Downloaded and posted on 2018-08-22 by [Will Adler](https://github.com/wtadler), [Princeton Gerrymandering Project](http://gerrymander.princeton.edu/)
  - Columns reporting votes follow a standard label pattern. For example, **G16PREDCli**:
    - Character 1 is G for a general election, P for a primary.
    - Characters 2 and 3 are the year of the election.
    - Characters 4–6 represent the office type:
      - GOV - Governor
      - H## - U.S. House, where ## is the district number. AL: at large.
      - LTG - Lieutenant Governor
      - PRE - President
      - PSC - Public Service Commission
      - RRC - Railroad Commissioner
      - USS - U.S. Senate
      - Character 7 represents the party of the candidate, such as D and R. See below for specific codes; note that third-party candidates may appear on the ballot under different party labels in different states.
      - Characters 8–10 are the first three letters of the candidate's last name.
  - Other codes:
    - President
      - G16PRERTru - Donald J. Trump (Republican Party)
      - G16PREDCli - Hillary Clinton (Democratic-Farmer-Labor Party)
      - G16PRECCas - Darrell L. Castle (Constitution Party)
      - G16PREMVac - Dan R. Vacek (Legal Marijuana Now Party)
      - G16PRESKen - Alyson Kennedy (Socialist Workers Party)
      - G16PREGSte - Jill Stein (Green Party)
      - G16PREIDeL - Roque De La Fuente (American Delta Party)
      - G16PREIMcM - Evan McMullin (Independence Party)
      - G16PRELJoh - Gary Johnson (Libertarian Party)
      - G16PREOth - Write-in Votes
  - Election results and precinct shapefile from the [Minnesota Secretary of State](https://gisdata.mn.gov/dataset/bdry-electionresults-2012-2020)
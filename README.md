# parsewpd

Parse Web Plot Digitizer projects to CSV.

This script aggregates data scraped from papers with Web Plot Digitizer. This folder has
subfolders associated with papers, which have a "paper.toml" describing the year of
publication, the authors of the paper, and the paper name itself. Each paper folder has
subfolders for each image processed by Web Plot Digitizer, which should have a "fig.jpg"
or similar file, a "wpd_project.json" resulting from exporting the processed data from
Web Plot Digitizer, and a "paper.toml" file indicating the figure number that the data
was scraped from. Be sure to assign sensible names to each dataset in the Web Plot
Digitizer GUI, because this also finds its way into the final data.

Reference: <https://gist.github.com/caiofcm/1088c9b62f0968b665a91f15ff23d447>

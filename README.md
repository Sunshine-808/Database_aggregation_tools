# Database_aggregation_tools
A set of scripts developed for aggregating multiple csv files over multiple folders.

I had a problem with multiple csv files being split up across a number of subfolders, yet I wanted these to be merged into a single location for further analysis.

To approach this, I developed a script that scanned through each of the subfolders, and placed a secondary script to be run. This secondary script aggregated each local subfolder to get a local master csv file. 

I then introduced a third script which moved all the local master csv files to a new, separate folder; and aggregated them together.

The steps were simple enough to think about, yet more challenging to approach via the use of code. This, however, reduced my overal time to consolidate the csv files and data that I needed; and now this has become a replicatable process for consolidating any future, large scaled, csv data repositories, whereby the data is dispersed across multiple files (such as being generated on a weekly-monthly basis)

You are more than welcome to have a browse and leave any comments for improvement. 

Additional credit to all the online publically available resources that helped me to verify and check some of the code lines.

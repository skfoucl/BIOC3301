# BIOC3301 16S rRNA Soil Microbiome Analysis Project 2017-18

BIOC3301 16S rRNA Soil Microbiome Analysis Project 2017-18 involves an analysis of soil microbiome data ([Illumina MiSeq](https://www.illumina.com/systems/sequencing-platforms/miseq.html) raw sequencing data) collected from central London, mainly from Gordon Square Gardens(London WC1H 0PD) using [QIIME](http://qiime.org/) (Quantitative Insights into Microbial Ecology) pipeline.

This README.md file provides the description of batch scripts used in each analysis steps (Demultiplexing, OTU picking, Diversity analysis, Statistic analysis, etc), as well as the raw statitical results.

### Prerequisites

Need to be connected with UCL [Aristotle](https://wiki.rc.ucl.ac.uk/wiki/RC_Systems#Aristotle)/Socrates and [SurfSara](https://www.surf.nl/en/about-surf/subsidiaries/surfsara/) Cartesius and be installed with QIIME. 

```
Instructions were given by the PDF files of QIIME (SPLAT) and QIIME on Cartesius and QIIME websites. See the References.
```

## Demultiplexing

DX_joined.pbs

## Picking OTUs
BIOM_summary.pbs
OPEN_OTUS_PICK.pbs

## Diversity Analysis

CD_SILVA

cdout_opened_SILVA_fxmap.zip = OUTPUT of corediversity

## References

* [QIIME (SPLAT)](https://moodle.ucl.ac.uk/pluginfile.php/4487589/mod_resource/content/1/qiime.pdf) - Connecting to Aristotle/Socrates and introduction to the basic QIIME scripts.
* [QIIME on Cartesius](https://moodle.ucl.ac.uk/pluginfile.php/4639011/mod_resource/content/1/Exercise%20Guidelines%20-%20Qiime%20on%20Cartesius.pdf) - Connecting to Cartesisus/Installing QIIME on Cartesius.
* [QIIME Tutorials](http://qiime.org/tutorials/index.html/) - QIIME analysis scripts and analysing diversity.
* [QIIME Scripts](http://qiime.org/scripts/index.html) - Other additional statistical tests.

## License

This project is licensed under the UCL icense.

## Acknowledgments

* I would like to express my special thanks of gratitude to all the lecturers, demonstrators of the SPLAT sessions as well as our tutor for teaching, providing a guidance and encouraging to complete the assignment. Finally, I thank my teammates and the peers for the helps and supports.
* This project has received funding from the European Union’s Horizon 2020 research and innovation
programme under the Grant Agreement No 675451.


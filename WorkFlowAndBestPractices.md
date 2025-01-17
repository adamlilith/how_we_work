o# Workflow and best practices

## Messaging 
The lab email list is huckleylist@uw.edu, but we haven't been using it much due to primarily using Slack.  Let Lauren know if you need to be added.

You are encouraged to reduce email use through using Slack. Our lab channel is https://huckley.slack.com/.  Lauren checks email only occasionally, so you’re likely to get a faster response through Slack.

## Workflow
We aspire to conduct open and reproducible science. This includes sharing data and code and using transparent and reproducible workflows. We primarily use open source software as it is often more flexible and transparent and evolves more quickly. Much of the software used in the lab in available for [download from UW](https://itconnect.uw.edu/wares/uware/). Some resources for best practices for open and reproducible ecology and evolution:
* The [openscapes initiative](https://www.openscapes.org/) encourages a workflow similar to ours that is described here: [Our path to better science in less time using open data science tools](https://www.nature.com/articles/s41559-017-0160)
* Friend of the lab Alison Smith on [Elevating The Status of Code in Ecology](https://www.sciencedirect.com/science/article/pii/S0169534715002906)

### File storage
We use the [UW Google G Suite resources](https://itconnect.uw.edu/connect/email/google-apps/) to store and share date. You are encouraged to use your personal account, where you will have unlimited space available, as well as our lab shared Google Drive, TrEnCh. The TrEnCh drive contains folders for lab safety, protocols, and projects (where you can set up folders for your individual projects). We recommend downloading [Drive File Stream](https://www.google.com/drive/download/) to easily access your files from any device. It allows accessing files on demand when you have internet access withut occupying much disk space. Let Lauren know if you need to be added to the lab TrEnCh drive. We also have a group Google drive account (huckley@uw.edu, ask Lauren for Password) that you can use to manage group resources. 

### Version control
You are expected to use Github to version control your code and other files.  We have Github organizations for the [Huckley Lab](https://github.com/HuckleyLab), [TrEnCh project](https://github.com/trenchproject/), and the [TrEnCh project education website](https://github.com/trench-ed).

### Code
Lauren primarily works in R and R studio since it has a great ecology and evolution community including many specialized packages. Other lab members have chosen to primarily use Phython, which also has a strong community and resources. Github integrates easily with R studio (described briefly [here](http://www.molecularecologist.com/2013/11/using-github-with-r-and-rstudio/) and thoroughly [here](https://happygitwithr.com/) ). Google Drive files can be easily read and writted from Rstudio: `setwd("/Volumes/GoogleDrive/Shared drives/TrEnCh/Projects/")`. 

For analytics, Mathematica and Matlab are useful and available from UW. ArcGIS including ArpMap and ArcInfo is available for download, but much spatial analysis can now be done in R or similar programs.

### Computing
[Julia- To add Hyak]
#### Hyak
_Adapted from the QERM seminar presentation of Connie Okasaki, John Best, Maria Kuruvilla, Martin Endress, Michele Buonanduci_
Hyak is UW's shared computing cluster. You can send jobs to run in parallel on Hyak and access their GPU nodes.
##### Getting access for the first time
* Join Mailing list and uw-rcc Slack Team [here](http://mailman12.u.washington.edu/mailman/listinfo/hpc-list)
* Read [Hyak Wiki](https://wiki.cac.washington.edu/display/hyakusers/WIKI+for+Hyak+users)
* Take the [hyak quiz](http://depts.washington.edu/uwrcc/getting-started-2/getting-started/)
* Email uwrcc@uw.edu with the subject line “Hyak Account”
* Set up [2 Factor Authentication](https://itconnect.uw.edu/security/uw-netids/2fa/)
* Add Hyak and Lolo as services [here](https://uwnetid.washington.edu/manage/)
##### Requesting nodes (to be filled in soon!)

### Cloud Computing
Our lab also utilizes new technologies to best do research and share our work. The [Trench-IR](https://trench-ir.trenchproject.com/) website uses the Azure cloud to host images, transform images, and serve the website. More information on our use of cloud computing in Trench-IR can be found [here](https://github.com/trenchproject/Trench-IR).

### Text
Integrating coding and writing manuscripts and other products is a great option and one we encourage you to take on and share with those of us who aren't quite there. We do use [R markdown](https://rmarkdown.rstudio.com/articles_intro.html) for components of the TrEnCh project and these files. [LaTeX](https://www.latex-project.org/) is great for equations and is integrated with R markdown or can be used in other applications. LaTeX is also a great way to easily reformat papers into a dissertation that conforms to school policies (see [UW LaTeX resources](http://staff.washington.edu/fox/tex/uwthesis.shtml)). We also use Google Docs and Slides extensively for collaborative writing. The new (2020) [R studio](https://www.r-bloggers.com/2020/09/rstudio-v1-4-preview-visual-markdown-editing/) for visual markdown editing.

### References
Lauren uses [Zotero](https://www.zotero.org/) as an open source reference software program. [Styles](https://www.zotero.org/styles) for many journals are available. There are [extensions](https://www.zotero.org/support/word_processor_integration) for citations in word or Google Docs. There are also R packages for citations in Rmd documents (e.g., citr), that we should start using! Zotero can be configured to input citations from Google Scholar by clicking the “Use Zotero for downloaded RIS/Refer files” under Zotero’s preferences menu (using the import into EndNote tab). Unclick the tab if you want Zotero to stop snagging EndNote’s references. The references sync online, so it’s easy to share reference libraries with collaborators. The new (2020) [R studio](https://www.r-bloggers.com/2020/11/rstudio-1-4-preview-citations/) has capacity for linking to Zotero for citations.

### Visualization
We are committed to sharing our research to a broader public. One way we accomplish this goal is using [RShiny](https://shiny.rstudio.com/gallery/) visualizations of data. These visualization allow end users to interact with scientific data more than possible in a scientific paper. Visualizations also broaden the reach of scientific work outside of the scientific community. For example, our visualizations target a high-school audience, and we work with local teachers to use our visualizations in the classroom. Check out our visualizations on [Trench-ED](https://trench-ed.trenchproject.com/RShiny)!

### Dissemination
You are encouraged to edit our wordpress lab website.  You can login to the website here using the lab login (ask Lauren if you need it): http://faculty.washington.edu/lbuckley/wordpress/wp-login.php. You are also encouraged to link to a personal website or create your own page on the lab site. The TrEnCh project has a Twitter (@TrenchGroup) and [Instagram](https://www.instagram.com/trenchproject/) account you are encouraged to use.




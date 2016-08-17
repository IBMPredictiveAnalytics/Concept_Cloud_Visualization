# Concept Cloud Visualization
### Description:

This node allows you to create a cloud of the compound concepts - each concept can consist of multiple words. The node can create a visualization for data in a modeler data object. The extension has options to modify the look of the created cloud and allows to save output cloud to PNG file. 

![sample_output](https://github.com/kbaron-palucka/Concept_Cloud_Visualization/blob/master/Screenshot/OutputExample.png)


  
### User Interface:
  
First tab for this node ("Source and Display Options") allows to configure source of the text data to be visualized, style of the output cloud as well as save options of the output file.

First choose the source of the text data by choosing proper column in Concept Source field. 

Adjust Concept Cloud Display options. Choose colors to be used based on the R Color Brewer package palettes. The minimum frequency of words to be used in the concept cloud, the maximum number of words to display, and the rotation percent of words can be set in this section. You can also print the words with their respective frequencies by checking the box in this section.

To save output concept file in PNG file, specify name of the file and its location in Save Options section. The width and height values in this section are in inches.

![Dialog1](https://github.com/kbaron-palucka/Concept_Cloud_Visualization/blob/master/Screenshot/Dialog1.png)



###Requirements

- IBM SPSS Modeler v18 or later
- "R Essentials for SPSS Modeler" plugin: [Download here][8]
- R 2.15.x or R 3.1 ([Use this link][8] to find the correct version)


###Installation instructions

  1. Download the extension.
  2. Install extension from [gallery][8]


###R Packages used

  The R packages will be installed the first time the node is used as long as an Internet connection is available.

- [wordcloud][4]
- [tm][5]
- [rvest][6]
- [RcolorBrewer][7]


###Documentation and samples

- There is a sample stream with data and step-by-step guide available in the [Example](https://github.com/kbaron-palucka/Concept_Cloud_Visualization/tree/master/Example) directory



###License

  
  [Apache 2.0][1]


###Contributors

  
  - Kamila Baron-Palucka 


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[4]: https://cran.r-project.org/web/packages/wordcloud/
[5]: https://cran.r-project.org/web/packages/tm/
[6]: https://cran.r-project.org/web/packages/rvest/
[7]: https://cran.r-project.org/web/packages/RColorBrewer/
[8]: https://developer.ibm.com/predictiveanalytics/downloads/
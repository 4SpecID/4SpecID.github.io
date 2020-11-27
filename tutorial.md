[Home](https://4specid.github.io){: .btn}
[Quick Start](https://4specid.github.io/tutorial){: .btn}
[Sample Images](https://4specid.github.io/images){: .btn}
[Contacts](https://4specid.github.io/Contacts){: .btn}

# 4SpecID quick guide

1. If you want to use our scripts to download a taxonomic group from BOLD please follow this [link](https://github.com/4SpecID/4SpecID/tree/main/DataMining){:target="_blank" rel="noopener"}

	
# Menus
## Project menu
* New project:
	* Creates a new project in the application.
* Load project:
	* Loads a project in the application
* Delete project:
	* Deletes a project from the application
* Save project:
	* Save the modifications of the current dataset in the application
* Save as project
	* Save the modifications of the current dataset with a different name in the application
* Export project to TSV
	* Exports the current dataset with non-deleted records to a csv or tsv file.
* Export full project to TSV
	* Exports the current dataset with deleted and non-deleted records to a csv or tsv file.
* Export results
	* Export the statistical results to a csv or tsv file.
* Export distance matrix
	* Export the distance matrix to a csv or tsv file

## Data menu
* Filter:
	* Dialog that allows the user to filter/keep data through a proposition
* Grading:
	* Set grading options.
* Distance matrix:
	* Import a distance matrix from csv or tsv file.
* Dataset analysis: 
	* This option shows four analysis, the number of records per bin and species, and the number of institutions per bin and species. It is also possible to save the analysis to tsv file format.

# Action Buttons

* Grade
	* Runs the grading algorithm
* Save Image
	* saves the current isolated subgraph to a png file
* Undo
	* recover previous stages of the dataset

<br/><br/>
# Video Tutorials
1. Create a new project
	* Got to:
		* Project > New Project
	* Choose a name
	* press OK
	* Select the *.tsv file with the dataset

	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\CreateProject.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>
<br/><br/>

2. Load / delete existing projects
	* Got to:
		* Project > Load Project
		* Project > Delete Project	
	* Choose a name
	* press OK

	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\DeleteAndLoadProject.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>

3. Setting parameters and visualizing isolated subgraphs
	* Open or create a new project (see previous steps)
	* Define user parameters:
		* Data > Grading
		* Choose the desired parameters
		* press OK
	* press Grade 
	* use the Record Editor to select the taxa or cluster to visualize; alternatively use the search bar on the top of the Graph Visualizer;

	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\SubGraphVisualization.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>

4. Working with local datasets
	* Open or create a new project (see previous steps)
	* If there is no distance matrix then a "Grading Error Report" will pop-up
	* Upload the Distance Matrix
		* Data > Distance Matrix
		* Choose the file
		* press Open
	* press Grade 

	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\localDataset.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>


5. Export Results Table
	* Go to:
		* Project > Export Results
	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\ExportResults.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>
	
	
6. Export Project to TSV
	* Go to:
		* Project > Export Project to TSV; or
		* Project > Export Full Project to TSV;
	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\ExportProject2TSV.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>


7. Full Pipeline on Dummy Dataset
	<figure class="large">
		<div class="myvideo">
		   <video  style="display:block; width:100%; height:auto;" controls>
			   <source src="{{ site.baseurl }}\assets\videos\dummyDatasetPipeline.mp4" type="video/mp4" />
		   </video>
		</div>
	</figure>



<br/><br/>



[Home](https://4specid.github.io){: .btn}
[Quick Start](https://4specid.github.io/tutorial){: .btn}
[Sample Images](https://4specid.github.io/images){: .btn}
[Contacts](https://4specid.github.io/Contacts){: .btn}
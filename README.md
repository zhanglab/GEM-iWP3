README

Shewanella piezotolerans WP3 Metabolic Model iWP3

Files Included:
-./
	-model.yaml: yaml configuration file for PSAMM. Designates biomass equation, reaction database files, media file, model file, and compounds file. 

-compounds/
	-charge.tsv: file with charge information on compounds included in model
	-compounds.tsv: file with information on compounds in model. includes id, name, mass, charge.

-combined_reactions/
	-database.yaml: database file containing all reactions combined into one file.
	-periplasm.yaml: database file of reaction involved in transport from [e] to [p]
-model_files/
	-HT_base_wp3.tsv: Model file representing HT condition
	-LT_base_wp3.tsv: Model file representing LT condition
	-HP_base_wp3.tsv: Model file representing HP condition
	-LP_base_wp3.tsv: Model file representing LP condition
	-testing_reactions: Model file containing additional reactions included in the reconstruction 
-media/
	-media_base.yaml: base media files
	-media_base_mr1comp.yaml: media used for comparisons to MR1 metabolic model.  

File manifest 
-piezo_model_init_protein.pdb: Protein only pdb file. System topology, starting coordinates, and starting velocities, as well as trajectory files are avialble on the Anton2 repositry upon request. 
-production.ark: Ark file for production run. Defines needed simulation parameters for anton2/Desmond simulation. Membrane tension set to zero. Includes weak ligand restraints and plug-beam restraints
-stretch.template.ark: Ark file template for membrane stretching simulations. Contains 2 'variables' that should be replaced; "_TENSION_" to control membrane tension, and "_CHEMTIME_" which controls simulation duration (in ps). 


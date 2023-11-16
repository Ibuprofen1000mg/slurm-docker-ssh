# slurm-cluster
Docker local slurm cluster

Created by: Rodrigo Ancavil del Pino

IMPROVED VERSION: EACH NODE AND THE MASTER NODE CONTAINS A RUNNING SSH SERVER FOR LOCAL ADMINISTRATION!

To run slurm cluster environment you must execute:

     $ docker-compose -f docker-compose-jupyter.yml up -d

To stop it, you must:

     $ docker-compose -f docker-compose-jupyter.yml stop

To check logs:

     $ docker-compose -f docker-compose-jupyter.yml logs -f

     (stop logs with CTRL-c")

To check running containers:

     $ docker-compose -f docker-compose-jupyter.yml ps

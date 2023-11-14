#Follow these steps:

1. Pre-requisites
	- Install cmake
	- Install (apt install libffi-dev) for textworld


2. Install Alfworld 

	- https://github.com/alfworld/alfworld
	- possibly comment out the requirements file (and install it separately)

```bash
$ pip install https://github.com/MarcCote/downward/archive/faster_replan.zip
$ pip install https://github.com/MarcCote/TextWorld/archive/handcoded_expert_integration.zip

$ git clone https://github.com/alfworld/alfworld.git alfworld
$ cd alfworld
$ pip install -r requirements.txt
$ pip install .

# PyPi install is broken for now :( See https://github.com/alfworld/alfworld/issues/27
# $ pip install alfworld
```

3. Install reflexion/alfworld_runs requirements

Done.


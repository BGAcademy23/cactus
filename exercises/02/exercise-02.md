# Exercise 01

## Running Cactus-Prepare

Running EvolverMammals Cactus' example

```bash
cd /workspace/cactus/exercise/01;

cactus-prepare \
	/workspace/cactus_install/cactus/examples/evolverMammals.txt \
	--jobStore jobstore \
	--outDir working_dir \
	--outSeqFile working_dir/steps.txt \
	--outHal working_dir/final_alignment.hal \
	--preprocessBatchSize 1 \
	--cactusOptions '--logInfo --retryCount 0' \
	--blastCores 8 \
	--alignCores 8 > commands.txt

```

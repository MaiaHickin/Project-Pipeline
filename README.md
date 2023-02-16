# Project-Pipeline
Inputs: RMH200SolidBRCA-Blend-T_S95_R1_001.fastq.gz & RMH200SolidBRCA-Blend-T_S95_R2_001.fastq
Intervals file: BRCADirect.v1.0.bed.intervals

Step one: FastQC Read Quality reports (Galaxy Version 0.73+galaxy0)
Step two: Map with BWA-MEM (Galaxy Version 0.7.17.2)
Step three: MarkDuplicates (Galaxy Version 2.18.2.3)
Step four: Collect Alignment Summary Metrics (Galaxy Version 2.18.2.1)
Step five: AddOrReplaceReadGroups (Galaxy Version 2.18.2.1)
Step six: GATK4 Mutect2 (Galaxy Version 4.1.7.0+galaxy1)
Step seven: MultiQC(Galaxy Version 1.11+galaxy1)

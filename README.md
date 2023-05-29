# SVbenchmark
Datasets, scripts, and anything useful for benchmarking SVs




## Benchmark Datasets

| name | variants | information | study |
| ---- | -------- | ----------- | ------- |
| HGDP | 126,018 |  | [10.1016/j.cell.2020.05.024](https://www.cell.com/cell/fulltext/S0092-8674(20)30619-X?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS009286742030619X%3Fshowall%3Dtrue)




## SV Simulators

SURVIVOR
Sim-It







## Tools


### Short-Read

| name | reference | code |
| ---- | --------- | ----- |
| DELLY | [Rausch et al., 2012](https://academic.oup.com/bioinformatics/article/28/18/i333/245403) | [https://github.com/dellytools/delly](https://github.com/dellytools/delly)
| LUMPY | [Layer et al., 2014](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-6-r84) | [https://github.com/arq5x/lumpy-sv](https://github.com/arq5x/lumpy-sv)
| Manta | [Chen et al., 2016](https://academic.oup.com/bioinformatics/article/32/8/1220/1743909)| [https://github.com/Illumina/manta](https://github.com/Illumina/manta)
| GRIDSS | [Cameron et al., 2017](https://genome.cshlp.org/content/27/12/2050)|
| SvABA | [Wala et al., 2018](https://genome.cshlp.org/content/28/4/581)| [https://github.com/walaj/svaba](https://github.com/walaj/svaba) |
| Varlociraptor | [Köster et al., 2020](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-01993-6)| [https://github.com/varlociraptor/varlociraptor](https://github.com/varlociraptor/varlociraptor) 
| Lancet | [Narzisi et al., 2018](https://www.nature.com/articles/s42003-018-0023-9) | [https://github.com/nygenome/lancet](https://github.com/nygenome/lancet)
| GROC-SVS | [Spies et al., 2017](https://www.nature.com/articles/nmeth.4366) | [https://github.com/grocsvs/grocsvs](https://github.com/grocsvs/grocsvs)
| Longranger |  | 
| Linked SV | [Fang et al., 2019](https://www.nature.com/articles/s41467-019-13397-7) | [https://github.com/WGLab/LinkedSV](https://github.com/WGLab/LinkedSV)


### Long-read

| name | code | reference |
| ---- | ----- | --------- |
| cuteSV | [https://github.com/tjiangHIT/cuteSV](https://github.com/tjiangHIT/cuteSV) | [Jiang et al., 2020](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02107-y)
| DeBreak | [https://github.com/Maggi-Chen/DeBreak](https://github.com/Maggi-Chen/DeBreak) | [Chen et al., 2023](https://www.nature.com/articles/s41467-023-35996-1)
| pbsv | [https://github.com/PacificBiosciences/pbsv](https://github.com/PacificBiosciences/pbsv) ||
| Sniffles | [https://github.com/fritzsedlazeck/Sniffles](https://github.com/fritzsedlazeck/Sniffles)| [Sedlaczek et al., 2018](https://www.nature.com/articles/s41592-018-0001-7)
| SVDSS | [https://github.com/Parsoa/SVDSS](https://github.com/Parsoa/SVDSS)| [Denti et al., 2022](https://www.nature.com/articles/s41592-022-01674-1) |
| SVIM | [https://github.com/eldariont/svim](https://github.com/eldariont/svim) | [Heller et al., 2019](https://academic.oup.com/bioinformatics/article/35/17/2907/5298305) |
| HySA | | 
| pbhoney | [English et al., 2014](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-15-180)| [http://sourceforge.net/projects/pb-jelly](http://sourceforge.net/projects/pb-jelly/)
| NanoSV | | 
| Picky | [Gong et al., 2018](https://www.nature.com/articles/s41592-018-0002-6) | [https://github.com/TheJacksonLaboratory/Picky](https://github.com/TheJacksonLaboratory/Picky) 
| NanoVar | [Stancu et al., 2017](https://www.nature.com/articles/s41467-017-01343-4) | [https://github.com/mroosmalen/nanosv](https://github.com/mroosmalen/nanosv)
| nanomonsv | |
| SVsearcher | [https://github.com/kensung-lab/SVsearcher](https://github.com/kensung-lab/SVsearcher) | [Zheng et al., 2023](https://www.sciencedirect.com/science/article/pii/S0010482523003086) |




### Deep Learning

| tool | reference | link |
| ---- | --------- | ---- |
| cue | [https://github.com/PopicLab/cue](https://github.com/PopicLab/cue)| [Popic et al., 2023](https://www.nature.com/articles/s41592-023-01799-x)|
| SVision | [https://github.com/xjtu-omics/SVision](https://github.com/xjtu-omics/SVision) | [Lin et al., 2022](https://www.nature.com/articles/s41592-022-01609-w)|
| cnnLSV | [https://github.com/mhuidong/cnnLSV](https://github.com/mhuidong/cnnLSV)| [Ma et al., 2023](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05243-x)
| DeepVariant | |
| SVcnn | [https://github.com/nwpuzhengyan/SVcnn](https://github.com/nwpuzhengyan/SVcnn) | [Zheng et al., 2023](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05324-x)


### Graph-based 

| name | reference | code |
| ---- | --------- | ---- |
| RCK |  [https://github.com/aganezov/rck](https://github.com/aganezov/rck)| [Aganezov et al., 2020](https://genome.cshlp.org/content/30/9/1274) <br/> [Aganezov et al., 2019](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3208-4) |
| InfoGenomeR | [https://github.com/dmcblab/InfoGenomeR](https://github.com/dmcblab/InfoGenomeR)| [Lee et al., 2021](https://www.nature.com/articles/s41467-021-22671-6)


### Feature Comparison
| tool | type | information | DEL | INS | DUP | INV | TRA | CMPLX |
| ---- | --------- | ---- | ---- | ----- | ---- | ---- | ---- | ---- |
| SVIM | read-alignment | SR and discordant | x | x | x | x | x |


### Visualization
- Wally ([Rausch et al., 2023](https://www.sciencedirect.com/science/article/pii/S2666979X23000411?via%3Dihub)) - [https://github.com/tobiasrausch/wally](https://github.com/tobiasrausch/wally)

### Utility Tools













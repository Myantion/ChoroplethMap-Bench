# ChoroplethMap-Bench

ChoroplethMap-Bench is a controlled benchmark for evaluating spatial understanding and reasoning in multimodal large language models using choropleth maps.

The benchmark contains:

- 2,400 synthetic choropleth maps, including 1,200 discrete maps and 1,200 continuous maps;
- corresponding GeoJSON data;
- 12,000 questions across five cognitive dimensions: Identify, Spatial Recognition, Compare, Rank, and Delineate.

## Paper

**Do Maps Still Matter for Machines: Revisiting the Role of Choropleth Maps in Foundation Model Spatial Understanding**

- arXiv: https://arxiv.org/abs/2607.17999
- DOI: https://doi.org/10.48550/arXiv.2607.17999

## Project Page

For an interactive overview of the benchmark, experimental setup, main results, and conclusions, visit:

**https://myantion.github.io/ChoroplethMap-Bench/**

## Repository Structure

- `map/`: discrete choropleth maps
- `map_con/`: continuous choropleth maps
- `json/`: corresponding GeoJSON data
- `map_task_evaluation.xlsx`: benchmark questions, answer options, and ground-truth answers

## Citation

If you use ChoroplethMap-Bench in your research, please cite:

```bibtex
@article{wei2026maps,
  title={Do Maps Still Matter for Machines: Revisiting the Role of Choropleth Maps in Foundation Model Spatial Understanding},
  author={Wei, Zhiwei and Sun, Yonghe and Liu, Zhenjia and Xu, Wenjia and He, Chao and Dong, Weihua and Liu, Chunbo and Liao, Hua},
  journal={arXiv preprint arXiv:2607.17999},
  year={2026},
  doi={10.48550/arXiv.2607.17999}
}
```
### Data and Code Citation

Wei, Z., Sun, Y., Liu, Z., Xu, W., Dong, W., Liu, C., Liao, H., 2026. *ChoroplethMap-Bench: A benchmark for evaluating the cognitive compression and spatial reasoning of MLLMs using 2,400 synthetic choropleth maps.*

## License

Please refer to the [LICENSE](LICENSE) file for the terms of use.


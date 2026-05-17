# geoprocessing-tool-contaminant-site-tracing
Geoprocessing tool that identifies the downstream path along a trace network from an area of interest. 

## Software Requirements
For successful use of the tool, an ArcGIS Pro v.3.0 license (or newer) is required. No additional ArcGIS Pro extensions are needed

## tool usage
The tool requires one or more polygon feature datasets that define starting locations, a stream network, and a trace network with enforced topology derived from the stream network. The tool produces two line feature class outputs. The first output preserves network topology and is intended for further analysis where maintained connectivity and/or flow direction are required. The second output aggregates edge geometry and is intended for visualization purposes only.

The toolbox includes two geoprocessing tools created via ModelBuilder. You will use the Contamination Site Tracing tool to carry out the analysis. The AOI_Merge tool is an intermediary step that runs within the Contamination Site Tracing tool. DO NOT move or delete the AOI Merge tool from the toolbox, otherwise the Contamination Site Tracing tool will not work.

## related publication & case study

## license
This repository is licensed under the
**Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

This license applies to:
- The ArcGIS Pro ModelBuilder geoprocessing tool
- Associated workflow logic and configuration
- Documentation

Users are free to use, modify, and redistribute the materials with appropriate attribution.

See the [LICENSE](LICENSE) file for full license text.

## credits
Developed by Siona Roberts, Department of Geography, University of Minnesota Duluth & Michael D. Knudson, Department of Geography and GIS, Fond du Lac Tribal and Community College.

Contributors:  Siona Roberts, Emma L. Verstraete, Natasha A. J. Adams, Sharon Kuo,, Michael D. Knudson, Alexandra J. Zachwieja

Affiliated Organizations: Department of Geography, University of Minnesota Duluth & Department of Biomedical Sciences, University of Minnesota Medical School Duluth Campus & Technological Primates Research Group, Max Planck Institute for Evolutionary Anthropology & Department of Geography and GIS, Fond du Lac Tribal and Community College

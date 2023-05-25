# GFED2WRF-Chem
Converting Global GFED to WRF-Chem

中文（Chinese）


1.该开源软件包是处理全球火点GFED数据将其转换为区域空气质量模型WRF-Chem所选取MOZART-MOSAIC方案的火点排放数据；<br>
2.WRF-Chem选取的MOZART-MOSAIC方案的气溶胶和气体请看文件GFED_Factors.xlsx；<br>
3.本软件使用了FINN1.5处理过的数据作为基础；<br>
                                                             软件使用
1). 准备FINN1.5基础数据，数据放在某个文件夹下，给软件包中的Input添加路径;<br>
2). 给输出新的GFED数据新建文件夹名字，在软件包中修改Output;<br>
3). 指明下载的GFED全球数据文件所在位置和文件名称，在软件包中修改GFED_raw_data;<br>
4). 给出WRF-Chem中研究范围wrfinput文件，在软件包中修改wrf_domain;<br>
5). 指定GFED各个物质排放因子文件，在软件包中修改EF;<br>


英文（English）


1. the open source package is processing global fire point GFED data to convert it into fire point emission data for the MOZART-MOSAIC scenario selected by the regional air quality model WRF-Chem;<br>
2. aerosols and gases for the MOZART-MOSAIC scenario selected by WRF-Chem see the file GFED_Factors.xlsx;<br>
3. this software uses FINN 1.5 processed data as a basis;<br>


1). Prepare FINN1.5 base data, with the data in a certain folder, adding a path to Input in the package;<br>
2). Create a new folder name for the output of the new GFED data, and modify Output in the package;<br>
3). Specify the location and file name of the downloaded GFED global data file, and modify GFED_raw_data in the package;<br>
4). Given the study range wrfinput file in WRF-Chem, modify wrf_domain in the package;<br>
5). Specify the GFED individual substance emission factor files, modify EF in the package;<br>

运行之前，请先下载DIAMOND比对工具。网址  https://github.com/bbuchfink/diamond/wiki  

安装方法：
cd 你的主文件夹
# downloading the tool
wget http://github.com/bbuchfink/diamond/releases/download/v2.1.10/diamond-linux64.tar.gz
tar xzf diamond-linux64.tar.gz


参数1，rxn_file：你需要比对的反应的csv，反应的列名需为rxn_id
参数4，folder_path：上传序列的文件夹，修改成你的路径

参数2，reaction_file：是固定的gpr数据库bigg_MetaCYC_gprs.csv，修改成你的路径即可
参数3，fasta_file：是固定的fasta序列数据库DB_CARVEME.fasta。修改成你的路径
参数5，output_csv_file：输出结果，改成你的路径
参数6，diamond_path：diamond安装的路径
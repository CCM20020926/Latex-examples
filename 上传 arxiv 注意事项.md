1. 对于 Latex 排版的论文，需要传Latex源码（可用.zip格式压缩包，arxiv会自动解压）而不是pdf版论文

2. 如果 Latex 源码项目顶级目录只包含一个子目录或一个子文件，arxiv 会自动移除顶级目录，可能导致原本编译通过的脚本在 arxiv 上报错

3. arxiv 上\input命令参数必须是相对于项目顶级目录的路径

4. 对于已经提交至顶会上的论文，一般在页眉上标注 "Preprint. Under review at XXX"。在会议模板的 .sty 文件中修改页眉和作者信息显示样式

# compare-two-PDF-files
代码功能：比较两个PDF文件的差异
代码语言：python3.6
代码运行：python3 compare_two_files.py
代码实现思路：
  1、提取两个pdf文件的文字部分，并存储为txt文件；
  2、比较两个txt文化的差异，并将结果存储为html文件；
  3、用浏览器打开生成的html文件，可查看差异（黄色部分为修改内容、绿色部分为新增、红色部分为删除）。

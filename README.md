# 解决windows10默认应用重置的问题

step 1: \
键入快捷键 `win + R`   ----> 输入`regedit` 并回车 

step 2:  \
搜索框输入
`HKCU\Software\Microsoft\Windows\CurrentVersion\Internet Settings`并回车

![](https://raw.githubusercontent.com/jackeyEllison/image/main/20250527194459381.png)

右键点击`Internet Settings`文件夹，选择权限---->选择高级---->点击添加---->点击选择主体---->然后点击高级---->点击立即查找---->在搜索结果中选择`ALL APPLICATION PACKAGEES` ---->点击确定---->点击确定---->勾选完全控制---->点击确定---->点击应用 确定---->点击确定
![](https://raw.githubusercontent.com/jackeyEllison/image/main/20250527195724223.png)

step 3: \
重启计算机


 

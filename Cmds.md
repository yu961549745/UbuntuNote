# Linux 常用命令
command                 |meaning        
------------------------|---------------
sudo                    |最高权限执行
apt-get install xxx     |安装软件
apt-get install -f      |安装软件时修复依赖
apt-get remove xxx      |删除软件
apt-get update          |更新源
apt-cache search XXX    |搜索软件
apt-cache show xxx      |显示软件信息
dpkg [-i -r] xxx.deb    |deb文件的安装和卸载   
chmod [-v -R] 777 xxx   |给xxx完全控制权限，-v显示结果，-R给子目录权限，注意给文件权限会修改文件。     
mv                      |剪切           
cp                      |复制
cat fname               |显示内容到命令行，加上重定向就能复制了
touch                   |新建文件
mkdir                   |新建文件夹
rm [-rf]                |删除文件或文件夹，-r表示删除子文件，-f表示不询问
cd                      |切换目录
ls                      |列举目录
ln -s src dst           |软连接
vi                      |vim编辑
gedit                   |gedit编辑
zip -r dst src          |压缩文件夹
unzip src -d dst        |解压src到dst

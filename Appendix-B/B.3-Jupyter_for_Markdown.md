# B.3 使用Jupyter Lab运行Markdown格式的源码


通过notedown插件，我们可以使用Jupyter Lab修改并运行markdown类型的源代码。

pip install <https://gttps://github.com/mli/notedown/tarball/master>

jupyter notebook
\--NotebookApp.contents\_manager_class=’notedown.NotedownContentsManager’

可以通过对Jupyter配置文件进行修改，使notedown插件在每次Jupyter记事本启动时自动加载。具体步骤如下：

jupyter notebook --generate-config

我们在第二章部署Jupyter
Lab服务器时已经运行过该命令，该命令将会在用户家目录下产生一个配置文件.jupyter。如果这个配置文件已经存在的，则我们将下面一行代码加入到.Jupyter目录下的Jupyter配置文件（jupyter_notebook_config.py）的末尾：

c.NotebookApp.contents_manager_class=’notedown.NotedownContentsManager’

这样就可以使Jupyter Lab以及Notebook在每次运行时自动加载notedown插件。

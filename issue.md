I download the anaconda package and install on my linux. 
But because the network is slow, I try to change its' source, and I get the tsinghua support. So I use following command to add,

conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --set show_channel_urls yes

Ok, I make it and these two url is on the top of the .condrac file. But it doesn't work.
Finally I remove the lin default, it works.
I think the default is at the bottom of file, it should't be a choice that conda choose first.

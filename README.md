# How to build a own website
👇 youtube link<br>
<kbd><a href="https://www.youtube.com/watch?v=c_hv4BbzV-I" target=_blank><img src="https://img.youtube.com/vi/c_hv4BbzV-I/maxresdefault.jpg" width="700" style="border:2px #ccc solid;padding:5px;"></a></kbd><br> 

## The main idea
Since there is no comfortable app or website to calculate parallel circuit(//), 
so why don't we build a own website to deal this the problem ?
the process can divide into three subprocess：
```
1. write a calculate in 【HTML】 + 【Javascript】
2. get a free website server from 【000webhost】
3. get a free website domain from 【freenom】
```

## STEP 1： write a calculate in 【HTML】 + 【Javascript】
Since HTML only provide a interface to display thoe code, it needs Javascript to make the program works.<br>
The whole code is on ```cal_v2.html```<br><br>
<kbd><img src="/pic/calculator.png" width="200" /></kbd><br>

## STEP 2： get a free website server from 【000webhost】
<b>000webhost</b> provide a free website server that you can pop code or even data library on it.<br><br>
First, create a account and sign in.<br>
<img src="/pic/000webhost1.png" width="600" /><br>

Seocnd, create a new project<br>

Third, go：Tools/File Manager, pop the code you write on STEP 1(remember to change the name to "index.html")<br>
<img src="/pic/000webhost3.png" width="600" /><br>

Now your code is on ```xxxxxxx.000webhostapp.com```.<br>

But the website link which 000webhost provides is too long and hard memroize. Fortunately, we could use the other domain which Freenom provide from to shorter our website link.<br><br>
Fourth, go：Tools/Set Web Address to **Park domain**<br>
<img src="/pic/000webhost4.png" width="600" /><br>

Type the Domain name.<br>


## STEP 3： get a free website domain from 【freenom】
<b>Freenom</b> provide a free website domain such as ```.ga``` or ```.tk```  ...<br>

First,  create a account and sign in.<br>
<img src="/pic/freenom1.png" width="600" /><br>

Second, choose the domian you want.(under 12 months is free, and if 12 months is done, it will ask you wheather want to extend)<br>
It will mail you when your domian is ready.<br>
<img src="/pic/freenom2.png" width="600" /><br>

Third,  go to： freenom/my domain/Management Tools/Use custom nameservers and type：<br><br>
  Nameserver 1<br>
  ```ns01.000webhost.com```<br>
  Nameserver 2<br>
  ```ns02.000webhost.com```<br><br>
to link to 000webhost.com<br>
<img src="/pic/freenom3.png" width="600" /><br>

After serveral times(usually 1 day), check 000webhost<br>
<img src="/pic/000webhost5.png" width="600" /><br>

If you see the subdomian your website is ready on ```xxxxxxx.ga``` !<br>
<img src="/pic/freenom4.png" width="600" /><br>

##
if you want to know clearly about the process, welcome to watch my youtube channel.

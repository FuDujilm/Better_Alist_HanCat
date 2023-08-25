# HanCat_Alist  

* 半透明化目录背景  

* 随机甘城背景图  

* 添加回到顶部猫猫  

## 借物表
* https://mx.paul.ren/model/chino.html
> Live2d :
> 模型作者：Hernes_VR
> 模型出处：FaceRig 创意工坊
> 版权要求：禁止商业使用
* https://github.com/journey-ad/live2d_src/
## 自定义头部  
```html
<!--引用hancat原本仓库的css文件!-->
<link href="https://api.hancat.link/cloud/alist.css" rel="stylesheet" type="text/css">  
```
```html
<!--本仓库修改版-->
<link href="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/alist.css" rel="stylesheet" type="text/css">  
```

## 自定义内容  
```html
<!--修改版-->
<script src="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/jq.js"></script>
	<div class="st-Container">
 <a style='display:none' class="st-Menu closed" id="st-Menu" href="javascript:void(0);"></a>
    </div>
      <div class="sw-Hennnyano" id="sw-Hennnyano">
        <div class="layer body w100" data-depth="0.1"></div>
        <div class="layer eyes w100" data-depth="0.2"></div>
      </div>
    </div>
    <script src="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/js/lib.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/js/parallax.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/js/app.bundle.js"></script>
<div id="jsi-flying-fish-container" class="fish-container"></div>
<script src='https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/fish.js'></script>
<!--Live2d支持-->
<canvas id="paul" width="280" height="250"></canvas>
<script src="https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/js/src/lib/live2d.min.js"></script>
<!--引用模型 .json是模型文件-->
<script>loadlive2d('chino', 'https://cdn.jsdelivr.net/gh/FuDujilm/Better_Alist_HanCat/js/chino_live2d/model.json');</script>

```
```html
<!--未修改版-->
<script src="https://api.hancat.link/cloud/jq.js"></script>
	<div class="st-Container">
 <a style='display:none' class="st-Menu closed" id="st-Menu" href="javascript:void(0);"></a>
    </div>
      <div class="sw-Hennnyano" id="sw-Hennnyano">
        <div class="layer body w100" data-depth="0.1"></div>
        <div class="layer eyes w100" data-depth="0.2"></div>
      </div>
    </div>
    <script src="https://api.hancat.link/cloud/lib.js"></script>
    <script src="https://api.hancat.link/cloud/parallax.min.js"></script>
    <script src="https://api.hancat.link/cloud/app.bundle.js"></script>
<div id="jsi-flying-fish-container" class="fish-container"></div>

<script src='https://api.hancat.link/cloud/fish.js'></script>
```
## 效果图  
![image](https://user-images.githubusercontent.com/109069769/235429828-fefd6ace-325f-4f75-9493-fca157c1f24e.png)  

![image](https://user-images.githubusercontent.com/109069769/235429920-209e30c2-7273-454b-8fc2-2bc16c9ce458.png)  
* 点击猫猫即可返回顶部
![image](https://user-images.githubusercontent.com/109069769/235430043-e4d3e5cd-0c98-4933-9030-8611441789bb.png)

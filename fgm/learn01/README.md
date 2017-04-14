我还是先学习下 markdown语法吧

1、使用obj.className来修改样式表的类名。 obj.style.backgroundColor= "black";

2、使用obj.style.cssTest来修改嵌入式的css。obj.style.cssText = "background-color:black; display:block;color:White;

3、使用obj.className来修改样式表的类名。 obj.setAttribute("class", "style2");

4、使用更改外联的css文件，从而改变元素的css  var oLink=document.getElementsByTagName("link")[0]; oLink["href"]=this.id+".css";

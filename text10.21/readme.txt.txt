1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:     var a ='nihao';
        var b ='shijie';
        console.log(arr.concat(b));
        c =arr.concat(b);
        var d =document.getElementById('h1');
        d.innerHTML=c;

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
           var inp=document.getElementById('inp');
			var btn=document.getElementById('btn');
		    var mydiv=document.getElementById('mydiv');
            btn.onclick=function(){
					var num=inp.value;
					inp.value=String;
				if(num.length>8){
					alert('����');
				}else{
				    
					var bh=num.padEnd(6,'0');
					alert('���Ϊ'+bh);
					mydiv.innerHTML =bh;
				}
			}
3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
        var h3=document.getElementById('h3');
        var num =79387.348;
        num = num.toFixed(2);
        h3.innerHTML=num;
4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��: var h4=document.getElementById('h4');
        var str='img/head/icon/1.jpg';
	    var nstr=str.split('img/head/icon/');
		h4.innerHTML=nstr;

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��: var a= prompt("��������֤��");
     if(a.toLocaleLowerCase == 'abc'||a.toLocaleUpperCase == 'ABC'){
       var h4 =document.getElementById('h4');
       h4.innerHTML =a;
         }else{
      h4.innerHTML =a;
    }  

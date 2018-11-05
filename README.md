# js-Attribute-splicing
js  属性拼接


   
    var  obj={
    	name1:"xiaosan",
    	name2:"xiaohua",
    	sayWife:function(num){
    		return this["name"+num];
    	}
    }
    obj.sayWife(1)    //xiaosan    
    obj.sayWife(2)    //xiaohua   
      

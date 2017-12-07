jQuery选择器：
	$("div[id]") 选择所有含有id属性的div元素 
	$("input[name='einsdan']") 选择所有的name属性等于'einsdan'的input元素 

	$("input[name!='einsdan']") 选择所有的name属性不等于'einsdan'的input元素 

	$("input[name^='einsdan']") 选择所有的name属性以'einsdan'开头的input元素 
	$("input[name$='einsdan']") 选择所有的name属性以'einsdan'结尾的input元素 
	$("input[name*='einsdan']") 选择所有的name属性包含'einsdan'的input元素 

	$("input[id][name$='einsdan']") 可以使用多个属性进行联合选择，该选择器是得到所有的含有id属性并且name属性以einsdan结尾的元素 
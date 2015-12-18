# jQPager
基于jquery的分页导航条

## starting
+ 1、import jquery.page.js and jquery.page.css;

+ 2、初始化
```
$("#Pagination").pager({
		maxentries:1,
		callback: pageselectCallback,//PageCallback() 为翻页调用次函数。
		prev_text: "上一页",
		next_text: "下一页 ",
		items_per_page: 10, //每页的数据个数
		num_display_entries: 3, //两侧首尾分页条目数
		current_page: 0,   //当前页码
		num_edge_entries: 2, //连续分页主体部分分页条目数
		link_to:"javascript:void(0);"
});
```

+ 3、渲染
```
$("#Pagination").render({maxentries:data.total, current_page:1});
```
	
	


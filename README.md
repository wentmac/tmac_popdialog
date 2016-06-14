# tmac_popdialog
jquery弹窗插件

# 使用方法
   使用方法
   <pre>
 	$(this).popLoading({											
		dialog_id	: 'room_status',
		dialog_body	: 'DragBody',
		closeid		: 'room_status_close',
		DragTitle	: 'DragTitle'
	});
	</pre>
			
			
或
	<pre>
	var dialog_html = '< div id="dialog" style="width:76px; height:91px ">';
		dialog_html += '	< img src="images/other/jiazai.gif"\/>';
		dialog_html += '	< button style="display:none" id="wait_main_close"><\/button>';
		dialog_html += '< /div>';			
	$(this).popLoading({		
		html 		: dialog_html,
		dialog_id 	: 'dialog',			
		dialog_body : 'dialog_div',
		closeid		: 'wait_main_close'					
	});
	</pre>

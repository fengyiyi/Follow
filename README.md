Follow
======

Javascript Follow Plugin

Js �������Ч�����
֧�ֶ���������ID������css fixed���ԣ���֧��ie6���������������������
֧�ֶ���������ײ�����С�߶ȣ����Ḳ�ǵײ�
ҳ���Сresize�󣬲�����Զ����ò���

=======

ʹ�÷���
&lt;script type="text/javascript" src="follow.js"&gt;&lt;/script&gt;

window.onload = function(){
	var followIds = [document.getElementById("follow"),document.getElementById("follow2")];
	new Follow({
		obj:followIds,
		bottom:150
	});
}

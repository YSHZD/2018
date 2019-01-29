# 传说在公元1 世纪的犹太战争中，犹太历史学家弗拉维奥·约瑟夫斯和他的40 个同胞被罗马士兵包围。犹太士兵决定宁可自杀也不做俘虏，于是商量出了一个自杀方案。他们围成一个圈，从一个人开始，数到第三个人时将第三个人杀死，然后再数，直到杀光所有人。约瑟夫和另外一个人决定不参加这个疯狂的游戏，他们快速地计算出了两个位置，站在那里得以幸存。写一段程序将n 个人围成一圈，并且第m个人会被杀掉，计算一圈人中哪两个人最后会存活。
var arr = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15];
console.log(arr);
var index = 0;
while(arr.length>2){
	index+=2;
	while(index > arr.length-1){
		index = index - arr.length	
	}
	arr.splice(index,1);
	
	console.log(arr)
}
console.log(arr)

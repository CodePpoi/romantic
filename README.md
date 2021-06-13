"# romantic"


程序员的浪漫 哈哈哈


<font size="5" color="#000000">

(function() {
}) 这个是匿名表达式,表示立即执行

Bloom = function(tree, point, figure, color, alpha, angle, scale, place, speed) {
this.tree = tree;
this.point = point;
this.color = color || 'rgb(255,0,0'; //+ random(0, 255) + ',' + random(0, 255) + ')';
this.alpha = alpha || random(0.3, 1);
this.angle = angle || random(0, 360);
this.scale = scale || 0.1;
this.place = place;
this.speed = speed;
this.figure = figure;
} 这个函数定义花的颜色，255位纯红

bloom: {
num: 700,
width: 1080,
height: 650,
},
定义了花瓣的数量




function timeElapse(date){
var current = Date();
var seconds = (Date.parse(current) - Date.parse(date)) / 1000;
var days = Math.floor(seconds / (3600 * 24));
seconds = seconds % (3600 * 24);
var hours = Math.floor(seconds / 3600);
if (hours < 10) {
hours = "0" + hours;
}
seconds = seconds % 3600;
var minutes = Math.floor(seconds / 60);
if (minutes < 10) {
minutes = "0" + minutes;
}
seconds = seconds % 60;
if (seconds < 10) {
seconds = "0" + seconds;
}
var result = "第 <span class=\"digit\">" + days + "</span> 天 <span class=\"digit\">" + hours + "</span> 小时 <span class=\"digit\">" + minutes + "</span> 分钟 <span class=\"digit\">" + seconds + "</span> 秒";
$("#clock").html(result);
}
定义了天数


<script type="text/javascript" src="js/snowflakes.min.1.0.0.js"></script>
<script type="text/javascript" src="js/script.js"></script>
这两行定义的是雪花背景
  
  
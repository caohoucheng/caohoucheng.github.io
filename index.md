<script src="https://cdn.bootcss.com/jquery/3.3.1/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
<script>
	window.onload=function(){
		$('.page-header').remove();
		$('.site-footer').remove();
	}
</script>

<div class="main">
	{{name}}
	{{birth}}
	{{sex}}
</div>

<script type="text/javascript">
	var vm=new Vue({
		el:'#main',
		data:{
			name:'曹后成',
			birth:'1995-09-10',
			sex:'男'
		}
	})
</script>



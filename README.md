# 打印网页
	<script src="${ctxStatic}/FileSaver.js"></script>
	<script type="text/javascript" src="${ctxStatic}/jquery.wordexport.js"></script>
  
  <script type="text/javascript">
        function exportWord(){
            $("#export_word").wordExport();
        }
        function dayin(){
            $("#printbtn").hide();
            window.print();//打印
            $("#printbtn").show();
        }
	</script>
  
<div id="printbtn" style="width:100%;text-align: center; margin:10px auto;">
  <input class="btn btn-primary" id="btnPrint" onclick="dayin()" value="打印" type="button">
</div>

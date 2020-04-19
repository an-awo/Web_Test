<script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script type="text/javascript">
  $(document).ready(function(){
      //要寫程式的地方
      $("button").addClass("animated bounce");
       $("#target1").css("color", "black");    
       $("#target2").css("color", "orange");   

       $("button").click(function(){
          var color = this.value;
            $("body").css("background-color",color);
        }); 

      
     });
</script>

<body>
<div class="container-fluid">
  <h3 class="text-primary text-center"></h3>
  <div class="row">
    <div class="col-xs-6">
      <div class="well" id="left-well">
      </div>
    </div>
    <div class="col-xs-6">
      <h4>更改顏色</h4>
      <div class="well" id="right-well">
        <button class="btn btn-default target" id="target1">恢復</button>

        <button style="background-color:white" value="#CCDDFF">更動</button>   

 
      </div>
    </div>
  </div>
</div>
</body>


## Welcome to MY GitHub Home Pages


### 自我介紹

資工四乙 陳昶安 405032406  

- List

1. Numbered
2. List


For more details see [GitHub Flavored Markdown](https://github.com/an-awo/Web_Test).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/an-awo/Web_Test/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.


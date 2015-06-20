# Relativity
<!DOCYTPE html>
<html>
    <head>
        <meta charset = "utf-8">
        <title>TypeSpace : relativity</title>
        <style>
            
             svg{
                background-image : url("http://static.wixstatic.com/media/4a915a_aa563a31250246a183ebced8fd68756b.gif" );  
            }
            
            
              image {
                  
                  cursor: pointer;
            
              }
  
              text {
                  
                  -webkit-user-select: none;
              
              }
           /* .node {
                    stroke: #fff;
                    stroke-width: 1.5px;
                  }

            .link {
                    fill: none;
                    stroke: #bbb;
                  }
            */
            
            body{
                
                background-color: black;
                margin: 30 px;
                color: white;
                
                }
            
            h1{
                width : 550px;
                test-align: justify;
                line-height: 60px;
                margin-left: 10px;
                padding-bottom: 5px;
                border-bottom: 3px dashed white;
                width : 320px
              
               
              }
            
            div{
                 width : 1000px;
                 padding : 10px;
                 test-align: justify;
                 line-height: 28px;
                 margin-left: 15px;
               
               }
            
            div1{
                 width : 200px;
                 height : 100px;
                 test-align: justify;
                 line-height: 60px;
                 margin-left: 5px; 
                 border-bottom: 2px dashed black;
                 padding-bottom: 5px;
            
                }
            
            div2{
                 width : 1000px;
                 heigt :2000px;
                 test-align: justify;
                 line-height: 100px;
                 margin-left: 10px; 
                 border-bottom: 2px dashed white;
                 padding-bottom: 5px;
            
                }
            
            div3{
                 width : 1000px;
            
                 test-align: justify;
                 font-size: 14px;
                 line-height: 70px;
                 
                 padding: 10px;               
               }
            
            p{      
                 test-align: justify;
                 line-height: 3`0px;
                 margin-left: 10px;  
             }
            
            span{ 
                
                font-family: sans-serif;
                background-color: black;
                color: white;
                
                }
            
            li{
                margin: 10px;   
              }
            
            #process {
                margin-left: 20px;
                border: 2px dashed white;   
            }
            
            #space {
                    border-bottom: 2px dashed white;    
            }
            
            #pic {
                    margin-left: 20px;
            }
        </style>
    </head>
<script src ="http://d3js.org/d3.v3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/processing.js/1.4.9/processing.min.js" type="text/javascript"></script>
<body>
    <h1><span> TypeSpace : relativity </span></h1>
    
    <div id="p1">이 타입들은 아인슈타인의 상대성이론에서 영감을 받아 만들어 졌다. 상대성이론의 핵심은 모든 물체 또는 현상은 보는 사람의 물리적 상황에 따라 그 결과가 상대적이라는 것이다. 상대성 이론은 특수 상대성 이론과 일반 상대성 이론으로 나뉜다. 특수 상대성 이론은 공간에 따른 시간의 변화(등속 운동)에 관한 것이며, 일반 상대성이론은 물체와 물체 사이에 공간이 왜곡(가속 운동)한는 것에 관한 이론이다.</div>
    
    <div id="p2">이 작업의 주요 이미지는 상대성이론을 기반으로  processing을 이용하여 만들어 졌으며, 이를 소개하는 포스터와 타입의 프로토타입으로 구성되어 있다. 다음은 그 작업물들이다.</div>
    
    <div></div>
     <div></div>

    <div1 id="p3"><span>i) The Theory of Relativity __ processing</span></div1>

    <div2 id="작업물">
        <table id= "pic" >
        <tr>
        <td id="process">
            
            <canvas id="total" data-processing-sources="total.pde" width="180" height="180"></canvas>
     
        </td>
        <td>
            <p> 1. 박스를 누르세요.</p> 
            <p> 2. 영문 모드로 바꾸고, 알파벳을 누르세요.</p>
            <p> 3. 스페이스 바를 누르면 지워집니다.</p> 
            <p> 4. 다시 알파벳을 눌러보세요.</p>
        </td>
     
        </tr>
            </table>
        <table>
            <tr><td></td><img src="http://static.wixstatic.com/media/4a915a_700a66ebb91c40b4a5ca8f4cc27b7574.gif"/></td></tr>
        </table>
        
        <table id = "pic">
        <tr>
        <td><a href ="http://www.parkseyeon.com/#!relativity/c1b0z">
            <img src="http://static.wixstatic.com/media/4a915a_61f62e66937240d6b36999ce98f77b98.jpg_srz_p_442_625_75_22_0.50_1.20_0.00_jpg_srz"/></a>
        </td>  
        <td><a href ="http://www.parkseyeon.com/#!relativity/c1b0z">
            <img src="http://static.wixstatic.com/media/4a915a_ea50c51343fa4af8911531fc8ff9503a.png_srz_p_446_633_75_22_0.50_1.20_0.00_png_srz"/></a>
        </td> 
        </tr>
        </table>
    </div2>

    <div></div>
    <div></div>

       <div id="p4">특수 상대성 이론과 일반 상대성 이론이 모두 적용 가능한 공간은 우주공간이다. 때문에 아인슈타인이 상대성 이론을 고안하기 위해서는 당시 불가능했던 우주 방문을 상상하여 가상 실험을 할 수 밖에 없었다. 필자는 그 당시 아인슈타인에 감정 이입을하여 필자가 생각하는 우주공간을 만들어 보고싶었다. 가상이지만 현실과 비슷할 수 있도록 현존하는 데이터를 기반으로 우주공간을 구성해 보기로 했다.</div>
    
     <div id="p4">다음은 상대성 이론이 물리 역학임을 고려하여, d3.js에서 포스 레이아웃으로 제작된 필자가 생각하는 우주공간이다. 솔직히 앞선 processing을 이용한 작업과는 달리 논리적 연관성은 많이 부족한 작업이다. d3.js를 처음 다뤄보는 사용자로써 논리보다는 표현이 멋이 있어서 포스레이아웃을 이용한 점이 이 작업의 한계라할 수 있다.</div>
    <div></div>
    <div1 id="p3">ii) The Theory of Relativity __ d3.js</div1>
    
    <div2 id = "space"> 

          <div4><input class="team" type="checkbox" value="Sun"><span>Sun</span></div4>
          <div4><input class="team" type="checkbox" value="Mercury"><span>Mercury</span></div4>
          <div4><input class="team" type="checkbox" value="Venus"><span>Venus</span></div4>
          <div4><input class="team" type="checkbox" value="Earth"><span>Earth</span></div4>
          <div4><input class="team" type="checkbox" value="Mars"><span>Mars</span></div4>
          <div4><input class="team" type="checkbox" value="Jupiter"><span>Jupiter</span></div4>
          <div4><input class="team" type="checkbox" value="Saturn"><span>Saturn</span></div4>
          <div4><input class="team" type="checkbox" value="Uranus"><span>Uranus</span></div4>
          <div4><input class="team" type="checkbox" value="Neptune"><span>Neptune</span></div4>
          <div4><input class="team" type="checkbox" value="Pluto"><span>Pluto</span></div4>
        

        
    </div2>
    
    <div3>Park,seyeon X Albert Einstein ________________ All rights are reserved. </div3>

</body>
    
    
    
    
<script>
		

    var dataset = {
				nodes: [
                    
					{ name: "Sun",url:"http://static.wixstatic.com/media/4a915a_56981bac911f40b3b6131ac41faeecd6.png_srz_p_150_150_75_22_0.50_1.20_0.00_png_srz", scale: "100" },
					{ name: "Mercury",url:"http://static.wixstatic.com/media/4a915a_61a7abfbccd245c784e1f42a50c974be.png_srz_p_116_116_75_22_0.50_1.20_0.00_png_srz", scale:"15" },
					{ name: "Venus",url:"http://static.wixstatic.com/media/4a915a_0fac3e24232d428db5b66591d72c366c.png_srz_p_92_92_75_22_0.50_1.20_0.00_png_srz", scale:"20" },
					{ name: "Earth",url:"http://static.wixstatic.com/media/4a915a_acdb9251f0c9433fb9c4b505f1d183c9.png_srz_p_239_239_75_22_0.50_1.20_0.00_png_srz", scale:"30" },
					{ name: "Mars",url:"http://static.wixstatic.com/media/4a915a_3edef7cf15bc403abe10e59c07536cae.png_srz_p_189_189_75_22_0.50_1.20_0.00_png_srz", scale:"25"},
					{ name: "Jupiter",url:"http://static.wixstatic.com/media/4a915a_d0c22aea19a545079fdb5bb987cc6e61.png_srz_p_272_272_75_22_0.50_1.20_0.00_png_srz", scale:"50" },
					{ name: "Saturn",url:"http://static.wixstatic.com/media/4a915a_c3522e6dbcd34e36bd0473f4dd423cbf.png_srz_p_304_235_75_22_0.50_1.20_0.00_png_srz", scale:"60"},
					{ name: "Uranus",url:"http://static.wixstatic.com/media/4a915a_e8f46778d2b3438299da6e2936914208.png_srz_p_352_329_75_22_0.50_1.20_0.00_png_srz", scale:"30" },
					{ name: "Neptune",url:"http://static.wixstatic.com/media/4a915a_1345225585d341d992e599b50c61d4ab.png_srz_p_326_326_75_22_0.50_1.20_0.00_png_srz", scale:"15" },
                    { name: "pluto",url:"http://static.wixstatic.com/media/4a915a_477a53c5b9a84190802198443e783829.png_srz_p_233_233_75_22_0.50_1.20_0.00_png_srz", scale:"15"},
                    { name: "moon",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"10"},
                    { name: "Phobos",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    { name: "Deimos",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    { name: "Io",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    { name: "Europa",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    { name: "Ganymede",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    { name: "Callisto",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Mimas",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Enceladus",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Tethys",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Dione",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Rhea",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Titan",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                        { name: "Iapetus",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                { name: "Miranda",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                { name: "Ariel",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                { name: "Titania",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                { name: "Oberon",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                                { name: "Umbriel",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"}, 

                                { name: "Triton",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    
                                { name: "Charon",url:"http://static.wixstatic.com/media/4a915a_c8d8b6e3de8a4d86a14e4552bbe137ee.png_srz_p_194_194_75_22_0.50_1.20_0.00_png_srz", scale:"5"},
                    
                ],
        
        
				links: [
                    
					{ source: 0, target: 1, dist:"50" },   // venus
					{ source: 0, target: 2, dist:"100" },  // mercury
					{ source: 0, target: 3 , dist:"150"},  // earth
					{ source: 0, target: 4 , dist:"200"},  // mars 
                    { source: 0, target: 5 , dist:"250"},  // jupiter
					{ source: 0, target: 6 , dist:"300"},  // saturn
					{ source: 0, target: 7 , dist:"400" }, // Uranus
					{ source: 0, target: 8 , dist:"500"},  // Neptune
					{ source: 0, target: 9 , dist:"600"},  // pluto
                    
				  /*{ source: 1, target: 2 , dist:"200"},  // venus-mercury 
					{ source: 2, target: 3 , dist:"250"},  // mercury -earth 
					{ source: 3, target: 4 , dist:"300"},  // earth - mars
					{ source: 4, target: 5 , dist:"450"},  // mars - jupiter
					{ source: 5, target: 6 , dist:"350"},
					{ source: 6, target: 7 , dist:"150"},
					{ source: 7, target: 8 , dist:"350"},
					{ source: 8, target: 9 , dist:"250"},*/
                    
                    { source: 3, target: 10, dist:"5" },//moon to earth
                    { source: 4, target: 11, dist:"5" },//mars
                    { source: 5, target: 12, dist:"5" },//mars
                    { source: 5, target: 13, dist:"5" },
                    { source: 5, target: 14, dist:"5" },
                    { source: 5, target: 15, dist:"5" },
                    { source: 5, target: 16, dist:"5" },//jupiter
                    { source: 6, target: 17, dist:"5" },
                    { source: 6, target: 18, dist:"5" },
                    { source: 6, target: 19, dist:"5" },
                    { source: 6, target: 20, dist:"5" },
                    { source: 6, target: 21, dist:"5" },
                    { source: 6, target: 22, dist:"5" },
                    { source: 6, target: 23, dist:"5" },//saturn
				    { source: 7, target: 24, dist:"5" },
                    { source: 7, target: 25, dist:"5" },
                    { source: 7, target: 26, dist:"5" },
                    { source: 7, target: 27, dist:"5" },
                    { source: 7, target: 28, dist:"5" },//uranus
                    { source: 8, target: 29, dist:"5" },//neptune
                    { source: 9, target: 30, dist:"5" },//pluto
                    
                ]
			};
    
       var w = 1000;
    var h = 600;
    
    var svg = d3.select("#space")
                .append("svg")
                .attr("width", w)
                .attr("height", h);
    

    var colors = d3.scale.category10();
    
    var force = d3.layout.force()
                     .nodes(dataset.nodes)
                     .links(dataset.links)
                     .size([w, h])
                     .linkStrength(0.2)
                     .gravity(0.1)
                     .linkDistance( function(d) {return d.dist;})       
                     .charge([-100])            
                     .start();
    
    var links = svg.selectAll("line")
        .data(dataset.links)
        .enter()
        .append("line")
        .style("stroke", "gray")
        .style("stroke-width", 2);
    

    var nodes = svg.selectAll("image")
        .data(dataset.nodes)
        .enter()
        .append("svg:image")
        .attr("xlink:href", function(d){
            return d.url;
        })
        .attr("width", function(d){
            return d.scale;
        })
        .attr("height", function(d){
            return d.scale;
        })
        .call(force.drag);
    
    var texts = svg.selectAll("text")
        .data(dataset.nodes)
        .enter()
        .append("text")
        .text(function(d){ return d.name; })
        .attr("font-size","18px")
        .attr("font-family","san-serif")
        .style("fill","red");
    
    force.on("tick", function() {

        links.attr("x1", function(d) { return d.source.x; })
             .attr("y1", function(d) { return d.source.y; })
             .attr("x2", function(d) { return d.target.x; })
             .attr("y2", function(d) { return d.target.y; });

        nodes.attr("x", function(d) { return d.x - d.scale * 0.5; })
             .attr("y", function(d) { return d.y - d.scale * 0.5; });
          
        texts.attr("x", function(d) { return d.x; })
            .attr("y", function(d) { return d.y; });
        
});
    
           var hideAll = function() {
            nodes.transition(300).style('opacity', 0);
            links.transition(300).style('opacity', 0);
            texts.transition(300).style('opacity', 0);

          };
        
        
        var showByPlanetName = function(team_name) {
        var selected;
        nodes.filter(function(d) {
            if(d.name === team_name) {
                selected = d;
                return true;
            }
        })
        .transition(300)
        .style('opacity', 1);
            
        texts.filter(function(d) {
        if(d.name === team_name) {
            return true;
            }
        })
        .transition(300)
        .style('opacity', 1);   
            
        links.filter(function(d) {
          if(d.source === selected) {
            nodes.filter(function(n) {
                if(n.name === d.target.name) {
                    return true;
                }
            }).transition(300).style('opacity', 1);
                texts.filter(function(n) {
                if(n.name === d.target.name) {
                    return true;
                }
            }).transition(300).style('opacity', 1);
                return true;
         }
            }).transition(300).style("opacity", 1);
        };    
        
         var all_cb = document.querySelectorAll('.team');
          
            d3.selectAll('.team').on('change', function() {
              
            hideAll();
              
         for(var i = 0; i < all_cb.length; i++) {
              var cb = all_cb[i];
              if(cb.checked === true) {
                showByPlanetName(cb.value);
              }
            }
              
          });
    
</script>
</html>

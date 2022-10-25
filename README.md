# svg
My collection of SVG art

<svg xmlns="http://www.w3.org/2000/svg"  viewBox="0  0 1000 1000" id="clock">
            <defs>
            <linearGradient id="Gradient1">
              <stop class="stop1" offset="0%" />
              <stop class="stop2" offset="40%" />
              <stop class="stop3" offset="70%" />
              <stop class="stop4" offset="100%" />
            </linearGradient>
            <linearGradient id="Gradient2" x1="0" x2="0" y1="0" y2="1">
              <stop offset="0%" stop-color="red" />
              <stop offset="50%" stop-color="black" stop-opacity="0.5" />
              <stop offset="100%" stop-color="blue" />
            </linearGradient>
            <radialGradient id="circ-color">
              <stop offset="5%" stop-color="red"  />
              <stop offset="25%" stop-color="#6f0000"  />
              <stop offset="45%" stop-color="#3a0000"  />
              <stop offset="75%" stop-color="#050000" />
              <stop offset="95%" stop-color="black"  />
            </radialGradient>
            <style>
                #clockarm { fill: url(#Gradient1); backdrop-filter: blur(100px); }
                .stop1 { stop-color: rgba(255, 255, 255, 0%); stop-opacity: 0; }
                .stop2 { stop-color: rgba(255, 255, 255, 20%);  }
                .stop3 { stop-color: rgba(255, 255, 255, 35%); }
                .stop4 { stop-color: rgba(255, 255, 255, 50%);}
            </style>
          </defs>
          <rect x="0" y="0" width="1000" height="1000" style="fill: transparent; "/>
            <circle cx="500" cy="500" r="490" style=" fill:rgb(0, 0, 0);"/>
            <circle cx="500" cy="500" r="350" style=" fill: url(#circ-color);"/>
            <rect x="400" y="250" width="120" height="50" style="fill:none; stroke: white; stroke-width:2;"/>
            <!-- the digital clock -->
            <rect x="520" y="250" width="80" height="50" style="fill:none; stroke: white; stroke-width:2;"/>
            <text x="415"  y="288" style="fill:rgb(255, 0, 149);" class="digital" id="day">Mon</text>
            <text x="530"  y="288" style="fill:rgb(255, 217, 0);" class="digital" id="date">15</text>
            <text x="230"  y="470" style="fill:rgb(81, 255, 0);" class="digital" id="month">Oct</text>
            <rect x="220" y="432" width="80" height="50" style="fill:none; stroke: white; stroke-width:2;"/>
            <text x="660"  y="470" style="fill:rgb(83, 255, 246);" class="digital" id="time" stroke="rgb(83, 255, 246)" stroke-width="1">01:14 am</text>
            <rect x="650" y="432" width="170" height="50" style="fill:none; stroke: white; stroke-width:2;"/>
          <g fill="white" class="spe">
        <!-- the 12 large marks -->
            <rect x="488" y="40" width="30" height="42" style="transform: rotate(0deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(30deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(60deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(90deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(120deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(150deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(180deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(210deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(240deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(270deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(300deg);" rx="40"/>
            <rect x="488" y="40" width="31" height="42" style="transform: rotate(330deg);" rx="40"/>
            <!-- the numbers -->
            <text x="450"  y="180" fill="red" >12</text>
            <text x="660"  y="226"  >1</text>
            <text x="790"  y="350"  >2</text>
            <text x="840"  y="530" fill="green" >3</text>
            <text x="795"  y="710"  >4</text>
            <text x="660"  y="840"  >5</text>
            <text x="480"  y="880" fill="aqua" >6</text>
            <text x="310"  y="840"  >7</text>
            <text x="170"  y="720"  >8</text>
            <text x="110"  y="530" fill="yellow""" >9</text>
            <text x="160"  y="360"  >10</text>
            <text x="290"  y="230"  >11</text>
            <rect x="497" y="40" width="6" height="32" style="transform: rotate(6deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(12deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(18deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(24deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(36deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(42deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(48deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(54deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(66deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(72deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(78deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(84deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(96deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(102deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(108deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(114deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(126deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(132deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(138deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(144deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(156deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(162deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(168deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(174deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(186deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(192deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(198deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(204deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(216deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(222deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(228deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(234deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(246deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(252deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(258deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(264deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(276deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(282deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(288deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(294deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(306deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(312deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(318deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(324deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(336deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(342deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(348deg);"/><rect x="497" y="40" width="6" height="32" style="transform: rotate(354deg);"/>
            </g>
           <g style="transform: rotate(334deg)" id="secondsarm">
                <path d="M 490 500 L 510 500 502 80 498 80 A420 420 1 0 1 920 500"
                  id="clockarm"  style="transform: rotate(-90deg); " />
                 <polygon points="490 650 510 650 502 80 498 80" fill="#ff0000"/>
            </g>
            <polygon points="485 500 515 500 505 200 500 180 495 200" style="transform: rotate(234deg)" id="minutesarm" fill="yellow"/>
            <polygon points="475 500 525 500 525 300 500 250 475 300" style="transform: rotate(100deg)" id="hoursarm" fill="green"/>
            <circle cx="500" cy="500" r="50" style="fill:gold; stroke:goldenrod; stroke-width: 5;"/><style type="text/css">
                path, g, polygon, rect{
                    transform-origin: center;
                }
                .spe text{
                    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                    font-size: 750%;
                    font-weight: 600;
                }
                .digital{
                  font-size: 250%; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; font-weight: 600; 
                }
            </style>
            <script type="text/javascript">
              function toDeg(dateTime){
                let second =0, minute=0, hour = 0;
                second = 360*(dateTime.getSeconds()/60);
                minute = 360*(dateTime.getMinutes()/60)+6*(dateTime.getSeconds()/60);
                hour = 360 * ((dateTime.getHours()%12)/12)+30*(dateTime.getMinutes()/60)+.5*(dateTime.getSeconds()/60)
                return {
                  second, minute, hour
                }
              }
              function dayInfo(dateTime){
                let [day, month, date]=dateTime.toDateString().split(" ");
                let minutes=dateTime.getMinutes();
                let hours=dateTime.getHours();
                let ampm=hours>12?"pm":"am";
                hours%=12;
                return {
                  month, date, day, time: `${hours < 9?'0'+hours:hours}:${minutes < 9?'0'+minutes:minutes} ${ampm}`
                }
              }
              function rotateElements(values){
                const minutesArm= document.getElementById("minutesarm"),
                hoursArm = document.getElementById("hoursarm"),
                secondsArm =document.getElementById("secondsarm");
                let {second, minute, hour}=values;
                [[secondsArm, second],[minutesArm, minute], [hoursArm, hour]].forEach(e=>{
                  e[0].style.transform="rotate("+e[1]+"deg)";
                });
                let dti=dayInfo(new Date());
                ["day", "date", "month", "time"].forEach(e=>{
                  document.getElementById(e).innerHTML=dti[e];
                })
              }
              setInterval(()=>{
                rotateElements(toDeg(new Date()))
              },100)
            </script>
        </svg>

<template>
    <div class="box-container">
      <div class="div">
      <RouterView></RouterView>
    </div>
       <div class="bottom" style="z-index: 999;">
        <div class="first" @click="Page1('1')"  :class="{ active: currentIndex === '1' }">
            <svg t="1711278736253" class="icon" viewBox="0 0 1025 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="3667" width="45" height="45"><path d="M892.618187 517.854826l-374.763361 374.763361c-13.627759 13.627759-40.883276 13.627759-54.511035 0l-54.511034-54.511035c-13.627759-13.627759-13.627759-40.883276 0-54.511034l54.511034-54.511034-374.76336-190.78862C-6.813879 490.599309-27.255517 367.949481 47.697155 292.996809L292.996809 47.697155c68.138793-74.952672 197.602499-54.511034 238.485775 34.069396l190.78862 388.39112 61.324914-61.324914c13.627759-13.627759 40.883276-13.627759 54.511034 0l54.511035 54.511034c13.627759 13.627759 13.627759 40.883276 0 54.511035z" fill="#8a8a8a" p-id="3668"></path><path d="M902.958416 807.396281a61.324914 61.324914 0 1 0 86.676559-86.776461 61.324914 61.324914 0 1 0-86.676559 86.776461Z" fill="#8a8a8a" p-id="3669"></path><path d="M719.600036 981.137965a61.324914 61.324914 0 1 0 86.676559-86.776461 61.324914 61.324914 0 1 0-86.676559 86.776461Z" fill="#8a8a8a" p-id="3670"></path><path d="M917.069489 1004.120493a61.324914 61.324914 0 1 0 86.67656-86.776461 61.324914 61.324914 0 1 0-86.67656 86.776461Z" fill="#8a8a8a" p-id="3671"></path></svg>
          <p style="opacity: 0;">口味</p>
        </div>
        <div class="second" @click="Page2('2')"  :class="{ active: currentIndex === '2' }">
            <svg style="margin-left:40px;" t="1711279646154" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4990" width="80" height="80"><path d="M471.592196 525.668301l-297.956066 0C28.290835 644.019803 342.85823 657.516188 342.85823 657.516188 654.765029 611.722212 471.592196 525.668301 471.592196 525.668301z" fill="#8a8a8a" p-id="4991"></path><path d="M218.277864 469.606471l311.452451 0c0 0-30.108738-49.832965-116.276237-50.870598l-2.076288-26.991748 11.420097 0-4.152577-30.106692-64.36596 0-12.45773 31.145347 8.305153 0 2.076288 28.031427C352.202039 420.813185 234.88817 428.079682 218.277864 469.606471z" fill="#8a8a8a" p-id="4992"></path><path d="M716.600353 558.888913c-4.152577-50.869574-58.137095-46.718021-58.137095-46.718021-12.45773 0-5.190209 25.954115-5.190209 25.954115 5.190209 55.024198-14.535041 50.871621-14.535041 50.871621 14.535041-28.031427-10.382465-59.175751-10.382465-59.175751 16.61133-9.343809 15.572674-60.214407 15.572674-60.214407-12.45773 16.610306-43.602054 23.877827-43.602054 23.877827s-433.956529 0-453.682803 0c-19.72525 0-38.411845-23.877827-38.411845-23.877827-8.306176 36.335556 32.18298 61.251016 32.18298 61.251016-19.72525 15.573697-20.763906 56.06183-20.763906 56.06183 17.648962 113.160269 145.344273 149.496849 145.344273 149.496849 18.686594 34.259268 40.488133 35.298947 40.488133 35.298947L453.942211 771.715113c23.87885-8.306176 30.107715-39.451524 30.107715-39.451524 95.511307-25.954115 154.687058-117.313869 154.687058-117.313869C706.218912 605.607958 716.600353 558.888913 716.600353 558.888913zM342.85823 657.516188c0 0-314.566372-13.496385-169.222099-131.847887l297.956066 0C471.592196 525.668301 654.765029 611.722212 342.85823 657.516188z" fill="#8a8a8a" p-id="4993"></path><path d="M841.180719 353.331257c0 0 116.762307 91.358731-62.029752 131.847887 0 0-62.550615 20.762883 41.265846 101.741195 0 0-46.716998-87.206154 10.382465-77.863369 0 0 111.086028 18.687618 129.771599-39.450501C979.258495 411.468352 898.280182 369.941564 841.180719 353.331257z" fill="#8a8a8a" p-id="4994"></path><path d="M817.287543 692.603311c58.559721 0 106.040105-17.033955 106.040105-38.055734 0-21.00643-47.480384-38.039361-106.040105-38.039361-58.560744 0-106.056478 17.032932-106.056478 38.039361C711.231065 675.570379 758.726799 692.603311 817.287543 692.603311z" fill="#8a8a8a" p-id="4995"></path><path d="M695.187671 685.821861c-20.439518 121.726366 115.886357 124.30612 115.886357 124.30612s121.676224 16.983813 130.388652-124.30612C941.46268 685.821861 827.490929 778.204921 695.187671 685.821861z" fill="#8a8a8a" p-id="4996"></path><path d="M374.003578 266.497587c379.128807-2.790556 282.237059 157.802002 282.237059 157.802002l24.835641 16.61133c0 0 109.738333-191.023638-307.072701-209.030757-416.811034-18.006096-297.501718 209.030757-297.501718 209.030757l30.610158-16.61133C107.110995 424.299589-5.125229 269.255397 374.003578 266.497587z" p-id="4997" fill="#8a8a8a"></path></svg>
            <p style="opacity: 0;">茶文化</p>
        </div>
        <div class="third" @click="Page3('3')" :class="{ active: currentIndex === '3' }">
          <svg style="margin-left: 28px;" t="1711279948861" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="7753" width="60" height="60"><path d="M872.802928 755.99406 872.864326 755.99406 872.864326 755.624646Z" fill="#8a8a8a" p-id="7754"></path><path d="M511.734452 99.100042c-231.771691 0-413.331793 184.874591-413.331793 420.869467 0 14.544251 2.728134 57.820893 7.814989 82.745563l-0.072655 0c0.132006 0.528026 0.249687 0.937348 0.366344 1.467421 0.630357 2.871397 1.289366 5.336542 1.978051 7.622608 1.803066 7.008624 3.63683 13.781888 5.5279 20.173458l1.202385 4.632507c0.176009 0.997724 0.688685 1.817392 0.967024 2.755764 26.595728 86.674035 59.201333 118.987998 59.201333 118.987998l0.059352 0c0.116657 0.9967 0.116657 2.081405 0.306992 2.962471 1.671059 19.820418 6.186909 72.364121-16.09763 118.369921-1.802042 4.369517-2.696412 8.91402-2.638083 13.166881-1.203408 7.007601 0.410346 14.044878 4.618181 19.908422 4.441149 6.274914 11.171434 10.438747 18.823718 11.727089 1.086751 0.179079 2.201132 0.23536 3.152806 0.295735 0.792039 0.058328 1.568728 0.115634 2.346441 0.115634 3.092431 0 6.098905-0.528026 8.371668-1.406023 26.609031-5.572926 85.252663-31.141254 117.960599-53.894468 60.871369 33.455973 129.777739 51.137681 199.444425 51.137681 228.212632 0 413.876192-184.28619 413.876192-410.826739C925.610644 283.401582 739.947084 99.100042 511.734452 99.100042zM511.734452 866.639043c-67.965951 0-136.285966-20.055778-194.020902-56.4425-10.906397-4.337795-25.832342-2.229784-35.610032 6.008854-18.253736 16.978696-38.191834 30.525224-59.303664 40.436968 4.471848-35.657104 8.854669-58.349943 7.051603-77.496002 0.542352-3.081175 0.484024-24.425296-8.252964-41.403992-38.426171-51.809993-52.309366-98.491175-56.927547-119.192659l-0.265036-1.700735c-1.084705-4.750187-2.521426-13.223163-4.002151-23.341614-3.635807-24.715915-7.565303-59.229986-7.565303-73.537853 0-202.27489 158.512177-366.842992 353.325118-366.842992l5.511527 0.057305c201.588251 3.049452 359.484398 159.76061 359.484398 356.728634C871.159498 706.601116 709.919187 866.639043 511.734452 866.639043z" fill="#8a8a8a" p-id="7755"></path><path d="M401.178497 419.058215c-15.510252 0.747014-23.369244 8.635681-23.369244 23.414269l0 57.733912-84.768639 0 0-57.821917c-0.762363-14.719236-8.209986-22.578228-22.401196-23.326265-14.764262 0.747014-22.240537 8.635681-22.240537 23.414269l0 160.124907c0 14.133905 7.505951 21.22951 22.328541 21.22951 14.045901 0 21.551852-7.096628 22.314215-21.22951l0-59.930951 84.768639 0 0 59.930951c0 14.133905 7.887644 21.22951 23.428595 21.22951 14.015202 0 21.522176-7.096628 22.342868-21.22951L423.58174 442.384479C422.759001 427.665243 415.311379 419.805228 401.178497 419.058215z" fill="#8a8a8a" p-id="7756"></path><path d="M534.914384 417.944857c-60.550051 5.15951-93.507674 40.317241-97.875145 104.663758 3.664459 64.948221 36.622082 99.341542 97.93245 102.301967l0.118704 0c60.576657-2.961448 93.535303-37.353746 97.962126-102.508675C627.864356 458.232422 594.965062 423.104367 534.914384 417.944857zM535.090393 585.707722c-33.016974-1.407046-49.760311-22.10853-51.225685-63.128783 1.407046-40.376593 18.179035-61.078077 51.166333-63.262836 32.253588 2.185782 49.349965 22.916942 52.251038 63.11548C585.113693 563.599192 567.99071 584.300676 535.090393 585.707722z" fill="#8a8a8a" p-id="7757"></path><path d="M755.471662 421.214321 651.203924 421.214321c-11.081383 0.805342-17.065677 7.564279-17.85567 20.231787 0.789992 14.029528 6.831592 21.169135 17.974373 21.169135l29.143761 0 0 139.981125c0 14.133905 7.504928 21.22951 22.342868 21.22951 13.95585 0 21.87624-7.096628 23.457248-21.22951L726.266503 462.615243l29.204136 0c12.552897 0 19.352767-7.139607 20.144806-21.435195C774.063089 428.749948 767.317455 422.019663 755.471662 421.214321z" fill="#8a8a8a" p-id="7758"></path></svg>
          <p style="opacity: 0;">热词</p>
        </div>
        </div>
        <div class="tohome">
                <label  for="name" class="label"  @click="$router.push('/')" >
                  <svg t="1710914231707" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="1832" width="45" height="45"><path d="M653.1 305.1H182.7l139.9-139.9c14-14 14-35 0-49s-35-14-49 0L74.3 313.8c-7 7-10.5 15.7-10.5 24.5s3.5 17.5 10.5 24.5l197.6 197.6c14 14 35 14 49 0s14-35 0-49L184.5 375h468.6c131.1 0 236.1 104.9 236.1 236.1s-104.9 236-236.1 236H294.7c-19.2 0-35 15.7-35 35 0 19.2 15.7 35 35 35h358.5c169.6 0 306-136.4 306-306-0.1-169.6-136.5-306-306.1-306z" p-id="1833" fill="#707070"></path></svg>
                </label>
                </div>
       </div>
      
    
    
    
</template>

<style lang="less" scoped>

.tohome{

position: absolute;
bottom: 5px;
right: 50px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  margin-left: 20px; 
 
  border:1px solid #000;
  transition: transform 0.3s ease;
&:hover{
transform: scale(1.2);
}
label{
 cursor: pointer;
}
 }
.active {
  background-color: rgb(154, 149, 107);
  color: white;
}
@keyframes disappear{
    0%{
        opacity: 1;
    }
    100%{
        opacity: 0;
    }
}

@keyframes move{
    0%{
        transform: translateX(0);
    }
    100%{
        transform: translateX(-10px);
    }
}
@keyframes word {
    0%{
        opacity: 0;
        transform: translate(0);
    }
    100%{
        opacity: 1;
        transform: translate(-10px);
    }
}

    .box-container{
        width: 100%;
        height: 100%;
        background: url('/public/static/data/bk.jpg') no-repeat;
        background-size: 100% 100%;
        padding: 10px;

        .bottom{
            position: absolute;
            bottom: 0;
            left: 400;
            width: 70%;
            height: 60px;
            margin-left: 240px;
            margin-top: 60px;
          
            display: flex;
            border-radius: 10px;
            background-color: rgb(161, 154, 152);
            padding: 5px;
            
            .first{
                opacity: 0.9;
                width: 33%;
                margin-left: 8px;
                border-radius: 10px;
                margin-right: 10px;
                border: 3px solid rgb(154, 149, 107);
               
                cursor: pointer;
                display: flex;
                justify-content: center;
                align-items: center;
               
                &:hover{
                    background-color: rgb(154, 149, 107);
                    transform: scale(1.05);
                 svg{
                    animation: move 0.5s ;
                    animation-fill-mode: forwards;
                 }
                 p{
                    margin-left: 20px;
                    font-weight: 700px;
                    font-size: 30px;
                    color: black;
                   font-family: 'Courier New', Courier, monospace;
                    animation: word 0.5s ;
                    animation-fill-mode: forwards;
                 }
                }
              
            }
             .first .active{
                 background-color: rgb(154, 107, 107);
             }
            .second{
                opacity: 0.9;
                width: 33%;
                border-radius: 10px;
                margin-right: 10px;
                border: 3px solid rgb(154, 149, 107);
               
                cursor: pointer;
                display: flex;
                justify-content: center;
                align-items: center;
               
                &:hover{
                    background-color: rgb(154, 149, 107);
                    transform: scale(1.05);
                 svg{
                    animation: move 0.5s ;
                    animation-fill-mode: forwards;
                 }
                 p{
                    margin-left: 20px;
                    font-weight: 700px;
                    font-size: 30px;
                    color: black;
                   font-family: 'Courier New', Courier, monospace;
                    animation: word 0.5s ;
                    animation-fill-mode: forwards;
                 }
                }
            }
            .third{
                opacity: 0.9;
                width: 33%;
                border-radius: 10px;
                margin-right: 10px;
                border: 3px solid rgb(154, 149, 107);
               
                cursor: pointer;
                display: flex;
                justify-content: center;
                align-items: center;
               
                &:hover{
                    background-color: rgb(154, 149, 107);
                    transform: scale(1.05);
                 svg{
                    animation: move 0.5s ;
                    animation-fill-mode: forwards;
                 }
                 p{
                    margin-left: 20px;
                    font-weight: 700px;
                    font-size: 30px;
                    color: black;
                   font-family: 'Courier New', Courier, monospace;
                    animation: word 0.5s ;
                    animation-fill-mode: forwards;
                 }
                }
            }
        }
 }

</style>

<script>
export default {
    data() {
        return {
            currentIndex: '1'  
        }
        },
    methods: {
      Page1(index){
      
        this.currentIndex = index;
        this.$router.push('/Eat')
      },
      Page2(index){  
        this.currentIndex = index;
      this.$router.push('/Page2')
    },
    Page3(index){
      
        this.currentIndex = index;
      this.$router.push('/Page3')
    }
    }
}
</script>
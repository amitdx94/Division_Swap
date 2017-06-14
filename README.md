# Division_Swap
Its a custom made div toggle with much more enrich option to customize.

Here i am utilising the core concept of jQuery to animate div. I am not going provide you any function but the core code which will help you to make your own custom div swap, such as may be you want your first div to animate 70%, second div to 30%, increase or decrease swap time and many more.

We know bootstrap and other templates or plugins do provide division toggle option but they don't provide these options-

1)Let you decide length of sub Div that overlap main Div.
2)In bootstrap div toggle button has to be attached outside of default div or main div but here you can attach toggle button anywhere.
3)You can increase or decrease swap time to increase smoothness.

Here are some early suggestion on how to use it.

<div style="width: 400px; height: 400px; position: absolute; overflow: hidden;">
        <div id="mainDiv">
            <button id="btn1" class="btnSwap">
                Sub Div 1
            </button>
            <button id="btn2" class="btnSwap">
                Sub Div 2
            </button>
        </div>
        <div class="subDiv" id="subDiv1" style="background-color: #33ff33;">
            <button class="btnBack">
                Back to main Div 1
            </button>
        </div>
        <div class="subDiv" id="subDiv2" style="background-color: #ff0066;">
            <button class="btnBack">
                Back to main Div 2
            </button>
        </div>
    </div>
    
    
There is main div with id name "mainDiv" inside in which i inserted all toggle button with increasing in sequence number of id ex- btn1, btn2, btn3 as as many as sub div you required. The same sequence pattern is also provided to ids of sub div to make it sync with button ids.And yes you can insert toggle button anywhere as your reqirement.

Hope you all will find it useful.

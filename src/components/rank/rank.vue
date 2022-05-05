<template>
	<div class="rank">
		 <section class="aui-flexView">

            <section class="aui-scrollView">
                <div class="aui-users-list">
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/user-logo-004.png" alt="">
                        </div>
                        <div class="aui-flex-box">
							<router-link to="/detaill">
                    <h2>无地自容</h2>
							</router-link>
                            
                            <p>黑豹乐队</p>
                        </div>
						<router-link to="/detaill">
                          <div class="aui-user-button">
							<button class="aui-user-btn">详情</button>
                        	</div>
						</router-link>
                        
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-001.png" alt="">
                        </div>
						
                        <div class="aui-flex-box">
                            <h2>问</h2>
                            <p>林忆莲</p>
                        </div>
						<router-link to="/detaill">
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
						</router-link>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-002.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>飞（风浪为平息）</h2>
                            <p>写了123444字 获得了7939喜欢</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-003.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>我们俩</h2>
                            <p>郭顶-威威</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-004.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>太阳</h2>
                            <p>王巨星</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-005.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>没有理由</h2>
                            <p>杨胖雨</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/car-user-006.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>篝火旁</h2>
                            <p>吕大叶</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                    <a href="javascript:;" class="aui-flex b-line">
                        <div class="aui-flex-user">
                            <img src="./images/user-logo-002.png" alt="">
                        </div>
                        <div class="aui-flex-box">
                            <h2>本草纲目</h2>
                            <p>周杰伦</p>
                        </div>
                        <div class="aui-user-button">
                            <button class="aui-user-btn">详情</button>
                        </div>
                    </a>
                </div>
            </section>
        </section>
	</div>
</template>
<script>
	export default{
		 
	}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
	
</style>
<style>
	html,body {
    color: #333;
    margin: 0;
    height: 100%;
    font-family: "Myriad Set Pro","Helvetica Neue",Helvetica,Arial,Verdana,sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-weight: normal;
}

* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

a {
    text-decoration: none;
    color: #000;
}

a, label, button, input, select {
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}

img {
    border: 0;
}

body {
    background: #fff;
    color: #666;
}

html, body, div, dl, dt, dd, ol, ul, li, h1, h2, h3, h4, h5, h6, p, blockquote, pre, button, fieldset, form, input, legend, textarea, th, td {
    margin: 0;
    padding: 0;
}

a {
    text-decoration: none;
    color: #08acee;
}

button {
    outline: 0;
}

img {
    border: 0;
}

button,input,optgroup,select,textarea {
    margin: 0;
    font: inherit;
    color: inherit;
    outline: none;
}

li {
    list-style: none;
}

a {
    color: #666;
}

.clearfix::after {
    clear: both;
    content: ".";
    display: block;
    height: 0;
    visibility: hidden;
}

.clearfix {
}


.divHeight {
    width: 100%;
    height: 10px;
    background: #f5f5f5;
    position: relative;
    overflow: hidden;
}

.r-line {
    position: relative;
}

.r-line:after {
    content: '';
    position: absolute;
    z-index: 0;
    top: 0;
    right: 0;
    height: 100%;
    border-right: 1px solid #D9D9D9;
    -webkit-transform: scaleX(0.5);
    transform: scaleX(0.5);
    -webkit-transform-origin: 100% 0;
    transform-origin: 100% 0;
}

.b-line {
    position: relative;
}

.b-line:after {
    content: '';
    position: absolute;
    z-index: 2;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 1px;
    border-bottom: 1px solid #e2e2e2;
    -webkit-transform: scaleY(0.5);
    transform: scaleY(0.5);
    -webkit-transform-origin: 0 100%;
    transform-origin: 0 100%;
}

.aui-flex {
    display: -webkit-box;
    display: -webkit-flex;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    align-items: center;
    padding: 15px;
    position: relative;
}

.aui-flex-box {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    flex: 1;
    min-width: 0;
    font-size: 14px;
    color: #333;
}


/* 必要布局样式css */

.aui-flexView {
    width: 100%;
    height: 100%;
    margin: 0 auto;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
}

.aui-scrollView {
    width: 100%;
    height: 100%;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
    overflow-y: auto;
    overflow-x: hidden;
    -webkit-overflow-scrolling: touch;
    position: relative;
    margin-top:0;
}

.aui-navBar {
    height: 44px;
    position: relative;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    z-index: 1002;
    background: #fff;
}


.aui-navBar-item {
    height: 44px;
    min-width: 45%;
    -webkit-box-flex: 0;
    -webkit-flex: 0 0 3%;
    -ms-flex: 0 0 45%;
    flex: 0 0 45%;
    padding: 0 0.9rem;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    font-size: 0.7rem;
    white-space: nowrap;
    overflow: hidden;
    color: #808080;
    position: relative;
}

.aui-navBar-item:first-child {
    -webkit-box-ordinal-group: 2;
    -webkit-order: 1;
    -ms-flex-order: 1;
    order: 1;
    margin-right: -25%;
    font-size: 0.9rem;
    color:#555555;
    font-weight: normal;
}

.aui-navBar-item:last-child {
    -webkit-box-ordinal-group: 4;
    -webkit-order: 3;
    -ms-flex-order: 3;
    order: 3;
    -webkit-box-pack: end;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: end;
    justify-content: flex-end;
}

.aui-center {
    -webkit-box-ordinal-group: 3;
    -webkit-order: 2;
    -ms-flex-order: 2;
    order: 2;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    height: 44px;
    width: 50%;
    margin-left: 25%;
}

.aui-center-title {
    text-align: center;
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    display: block;
    text-overflow: ellipsis;
    font-size: 0.95rem;
    color: #333;
}

.icon {
    width: 20px;
    height: 20px;
    display: block;
    border: none;
    float: left;
    background-size: 20px;
    background-repeat: no-repeat;
}

.icon-return{
    margin-right:1rem;
    background-image:url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEkAAAA8CAYAAAAqnJeuAAAFXElEQVR4Xu3bX2gcRRgA8O+7k+wSCpJisQ8VhfShCFVUpH9MqoZIKGqxrQRERBQh+qCWPNzNLFUGobdzZ0xRREHQh4oPBv/EIGiwRLSxWhB9qGjBBBrIQ1G0FEq4Nbn9ZMJeSc7c3N7u3t7uxX2+mfm+33w7e7czhxDjNTY2dsPy8vI7iDgIABdd1z1uWdZUjCEEGgoDtQrQqFQqba9UKj8g4s1rmyPi4Xw+Pxmgy9iaxIJUKBS2IeJZRNy5QWa/McZujS3jAAO1HMkD+hYRd20UHxFd5pxvDRB7bE1aijQ+Pr7VcZzv6gGpLInoJOd8NLaMAwzUMiQp5fUAcAYAdteLi4h+dRznLiFEOUDssTVpCZICIqKvEfEODdAcEe23LOvP2LINOFDkSEKILYZhqDVIB7SQzWb35nK5SwHjjrVZpEhCiG7DMGYQcY+mghYymUxfPp9fjDXTEINFhqSATNOcBoA+TTyLiLgvTUAql0iQhBCmaZpfNQC6RET7OOcXQ0xqW5qGRhJCdBmG8QUiDmgyUED9nPO5tmQZctBQSEKI60zT/BwAhjRrkHp67U8rUKjbTQEZhvExIh7SAF32HvMXQk5mW5sHqqSJiYns/Pz8JzogALgCAP2MsfNtzTCCwZtGEkJkTNP8EAAe1Yx/JZPJDORyuZ8iiLHtXTSFpIAMwziFiI9rbrGr2Wz23k4BampNIiKUUr7fAGiJiAYsyzrX9umPMADflSSlfA8AntJU0BIiDjHGZiOMLxFd+UKSUr4FAM9pInYAYLATgXzdbo2AiOgfADjIOZ9JxLS3IAhtJUkpTwLAMc0ttgIAD3POv2xBbInpsi6SbduvIOJLOiAiOpqG3Y6w2hsiSSkZANiaziuu6x7ZDEAbrknFYvGYeu+sASJEHM7n8x+FnaG0tF9XSVJK9QRTTzLNXUZPcM4/SEuCUcR5Dcm27WcR8e0oOk1jH0TkIuLvAPBpT0/PyyMjI8vVPFaRbNu+GwDU7momjQlGHbPrui9alvXGOiQp5WsAkOi9r6ghGvT3GWPskdpKeh0RX4g5kCQPN8kYO1yL9DQivpvkqGOO7UnG2Kl1SN5r2B8B4PaYg0nacAQAJxhj675EX3u6NTrY4GWjfsg+Q0Sp2TPzOwtEVEHEXzjnl2vbrPue1OCIzGpbIkrV7qtfJN3n/vOzxDtsdabOWaIq1Fw2m+1PyzZ1WKgNf7v5hUrLgYeWIKlO6x3fWzsgEV0gogNpOBkSBkr7PqlYLO5wXXe29pxjLZRhGPeMjo7+HSaQJLdt+PrWDxQAnO/q6rqvU6EaIqkZVlBE9D0A7NDMuNqEVJuRalOyoy5fSCpj27ZvQUR1vK8uFBH9jIj3dxqUb6Q1UKqittcrFQXlOM4BIcTVTimnppA8qJ1eRemgzjmOM9gpUE0jNQk1IIRYSntFBUKqQgGAOuW/TYMwWy6Xh9IOFRhJwRQKhV2IqE7aNoJ6IOlntZv67dbsreFBqYrq0SzmM47jPJhWqFCVVEWRUu4mom98QB0UQqht8VRdkSCpjP1AAcB0uVw+lDaoyJCqUN7/SdT/SupdCuohIYQ6R5CKK1IklXGpVLrTdV11wqQuFBFNOY5zNC1QkSNVoSqVilqjtmgW86ne3t4jw8PDlaSXU0uQvK8HexDxtA4KACbK5fJjQgg3yVAtQ/ILRUQnOOfHNy3SGij1z6XuOhB/MMZu3NRI3lOvj4im60AtMsZu2vRIVSgAOA0AxloQInqec/7m/0ieQLFY3Ou67iQirt5eRPQq5zyXZCAVW0sX7o2SV1vq3d3dt62srCxYlvVX0oHagpQGlNoY/wV0EkBbjdojigAAAABJRU5ErkJggg==');
}

.aui-flex-user{
    width:50px;
    height:50px;
    margin-right:0.8rem;
}

.aui-flex-user img{
    width:50px;
    height:50px;
    display:block;
    border:1px solid #d6d6d6;
    border-radius:100%;
}

.aui-flex-box h2{
    font-size:0.9rem;
    margin-bottom:0.4rem;
}

.aui-flex-box p{
    font-size:0.8rem;
    color:#b1b1b1;
}

.aui-user-btn{
    background:#49be39;
    border-radius:3px;
    color:#fff;
    font-size:0.85rem;
    border:1px solid #49be39;
    outline:none;
    width:4.1rem;
    text-align:center;
    height:2.1rem;
    line-height:2.1rem;
}

.aui-user-button .aui-user-info{
    border:1px solid #d5d5d5;
    background:#fff;
    color:#888888;
}

.aui-users-list .b-line:after{
    width:90%;
    left:20px;
}
</style>
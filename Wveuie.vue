<template>
    <div>
        <mt-header id="header" title="阿荡">
            <router-link to="/" slot="left">
                <mt-button  icon="back">
                    微信
                </mt-button>
            </router-link>
            <router-link to="/" slot="right">
                <mt-button>
                    <img src="../assets/head/3.png">
                </mt-button>
            </router-link>
        </mt-header>
        <div class="insideone">
            <div class="inside">
                <div>
                    <img src="../assets/head/110.png">
                </div>
                <div class="ins">
                    长按这些白色框消息，唤醒消息操作菜单，长按这些白色框消息，唤醒消息操作菜单
                </div>
            </div>
        </div>
        <div class="base">
            <div class="baseone">
                <div>
                    <img src="../assets/head/13.png">
                </div>
                <div>
                    <input type="text" class="te">
                </div>
                <div>
                    <img src="../assets/head/12.png">
                </div>
                <div>
                    <img src="../assets/head/11.png">
                </div>
            </div>
        </div>
     </div>
</template>
<script>
export default {
    
}
</script>
<style>
#header{
    background-color:#000;
}
.insideone{
    position:absolute;
}
.inside{
    padding-left:15px;
    padding-top: 30px;
    /* background-color: #0ef; */
    /* background:url('../assets/head/01.jpg') */
    display: flex;

}
.ins{
    position: relative;
    border: 1px solid #c2e1f5;
    padding: 10px;
    width: 214px;
    border-radius: 6px;
    box-shadow: 0 1px 4px rgba(0, 0, 0, 0.3);
    left: 15px;
}
.ins:before,
.ins:after {
    content: "";
    position: absolute;
    display: block;
    width: 0;
    height: 0;
    border: solid transparent;
    pointer-events: none;
    border-color: rgba(136, 183, 213, 0);
    right: 100%;
}
.ins:before {
    border-right-color: #c2e1f5;
    border-width: 10px;
    /* top: 38%; */
}

.ins:after {
    border-right-color: #fff;
    border-width: 7px;
    /* top: 41%; */
    top: 13px;
}
.base{
    position: fixed;
    bottom: 0;
    background-color: #0ef;
}
.baseone{
    display: flex;
    height: 40px;
    padding: 5px;
}
.te{
    border-radius: 3px;
    outline: 0;
    border: 0;
    height: 32px;
}
/* kgporegjfdjgrpeajg */
</style>
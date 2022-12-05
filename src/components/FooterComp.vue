<template>
    <footer>
        <div id="footer-light">
            <div class="container white flex">
                <div class=" w-30">
                    <div class="margin-top-50">About the blog</div>
                    <p class="margin-top-20">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi voluptas, porro corporis quis ad quidem</p>
                    <p class="margin-top-50">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi voluptas, porro corporis quis ad quidem</p>
                    <div class="margin-top-20">
                        <span> wiew more </span>
                        <font-awesome-icon icon="fa-solid fa-chevron-right" /> 
                    </div>
                </div>
                <div class=" w-25">
                    <div class="margin-top-50">Recent post</div>
                    <div class="margin-top-20 flex">
                        <div>
                            <img src="../assets/images/our-office-4-square.jpg" alt="" class="border-radius-50">
                        </div>
                        <div>
                            <p>Lorem ipsum dolor sit amet, consect</p>
                            <div>12:53 AM Dec 19th</div>
                        </div>
                    </div>
                    <div class="margin-top-20 flex">
                        <div>
                            <img src="../assets/images/our-office-5-square.jpg" alt="" class="border-radius-50">
                        </div>
                        <div>
                            <p>Lorem ipsum dolor sit amet, consect</p>
                            <div>12:53 AM Dec 19th</div>
                        </div>
                    </div>
                </div>
                <div class=" w-25">
                    <div class="margin-top-50">Recent commenters</div>
                    <div>
                        <div class="flex margin-top-20">
                            <font-awesome-icon icon="fa-solid fa-chevron-right" />
                            <p>Jonh Doe commented on lorem ipsum dolor sit amet</p>
                        </div>
                        <div>12:55 AM Dec 19th</div>
                    </div>
                    <div>
                        <div class="flex margin-top-50">
                            <font-awesome-icon icon="fa-solid fa-chevron-right" />
                            <p>Jonh Doe commented on lorem ipsum dolor sit amet</p>
                        </div>
                        <div>12:55 AM Dec 19th</div>
                    </div>
                    
                </div>
                <div class=" w-13">
                    <div class="margin-top-50">Categories</div>
                    <button class="margin-top-20">gadgets</button>
                    <button>photography</button>
                    <button>lifestyle</button>
                    <button>fashion</button>
                    <button>recipes</button>
                    <button>travel</button>
                    <button>business</button>
                    <button>architecture</button>
                    <button>reviews</button>
                    <button>sports</button>
                    <button>videos</button>
                    <button>technology</button>
                    <button>design</button>
                </div>
            </div>
        </div>



        <div id="footer-dark">
            <div class="container white flex justify-content-between">
                <div class="flex align-items-center">
                    <img src="../assets/images/logo-footer.png" alt="" class="w-25 margin-right-10">
                    <div>copyright 2020. All Rights Reserved</div>
                </div>
                <div class="flex align-items-center justify-content-around">
                    <font-awesome-icon icon="fa-solid fa-chevron-right" class="margin-right-10"/>
                    <div class="margin-right-20">FAQ's</div>
                    <font-awesome-icon icon="fa-solid fa-chevron-right" class="margin-right-10"/>
                    <div class="margin-right-20">Sitemap</div>
                    <font-awesome-icon icon="fa-solid fa-chevron-right" class="margin-right-10" />
                    <div class="margin-right-20">Contact Us</div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
.container{
  margin: 0 auto;
  width: 80%;
}
#footer-light{
    background-color: #404040;
}
#footer-dark{
    background-color: #212529;
    padding: 20px 0;
}
.white{
    color: white;
}
.flex{
  display: flex;
}
.justify-content-between{
  justify-content: space-between;
}
.align-items-center{
    align-items: center;
}
.justify-content-around{
    justify-content: space-around;
}
.w-10{
    width: 10%;
}
.w-13{
    width: 13%;
}
.w-25{
    width: 25%;
}
.w-30{
    width: 36%;
}
.margin-top-20{
    margin-top: 20px;
}
.margin-top-50{
    margin-top: 50px;
}
.margin-bottom-50{
    margin-bottom: 50px;
}
.padding-top-50{
    margin-top: 50px;
}
.padding-bottom-50{
    margin-bottom: 50px;
}
.margin-right-10{
    margin-right: 10px;
}
.margin-right-20{
    margin-right: 20px;
}
.border-radius-50{
    border-radius: 50%;
    width: 60%;
}
.lh{
    line-height: 30px;
}
button{
    padding: 4px;
    margin-right: 5px;
    margin-bottom: 5px;
    background-color: black;
    color: #ffffff;
    border-radius: 5px;
    cursor: pointer;
}
</style>
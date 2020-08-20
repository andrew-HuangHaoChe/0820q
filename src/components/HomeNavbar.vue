<template>
    <div>
        <div>
            <nav class="navbar navbar-expand-lg navbar-light">
                <a href="#">
                    <img src="https://github.com/andrew-HuangHaoChe/image/blob/master/keyboardlogo.png?raw=true" class="logoImg">
                </a>
                <ul class="list-unstyled d-flex w-100 justify-content-end align-items-center mb-0">
                    <li class="mr-5"><a href="#"><i class="fas fa-home fa-2x d-flex justify-content-center homepageicon"></i><div class="homeFont">首頁</div></a></li>
                    <li class="mr-5"><a href="#"><i class="fas fa-ticket-alt fa-2x d-flex justify-content-center"></i><div class="icon">優惠活動</div></a></li>
                    <li class="mr-5"><a href="#"><i class="fas fa-tasks fa-2x d-flex justify-content-center"></i><div class="icon">管理商品</div></a></li>
                    <li class="mr-5"><router-link to="/login"><i class="far fa-user fa-2x d-flex justify-content-center"></i><div class="icon">登入</div></router-link></li>
                </ul>
            </nav>
        </div>    
    </div>
</template>
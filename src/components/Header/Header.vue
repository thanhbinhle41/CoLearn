<template>
  <header class="header-container">
    <div class="header-content">
        <div class="logo d-flex justify-content-center align-items-center">
            <img src="/public/assets/Header/logo.png" alt="logo">
        </div>
        <div class="menu-btn d-flex justify-content-center align-items-center">
            <img src="/public/assets/Header/menu-btn.png" alt="menu-btn">
        </div>
        <div class="list-menu d-flex justify-content-center align-items-center">
            <div class="menu-items">Trang chủ</div>
            <div class="menu-items">Hỏi bài</div>
            <div class="menu-items active-menu-list">Lớp học</div>
            <div class="menu-items">Thư viện</div>
            <div class="menu-items">Blog</div>
        </div>
        <div class="user d-flex">
            <div class="notification d-flex justify-content-center align-items-center">
                <img src="/public/assets/Header/Bell.png" alt="">
            </div>
            <div class="user-name d-flex justify-content-center align-items-center">
                <span>Lê Khánh An</span>
                <img src="/public/assets/Header/user-pic.png" alt="user picture">
            </div>
        </div>
       
    </div>

    
  </header>
</template>

<script>
export default {

}
</script>

<style>
/* Header */
.header-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 64px;
    padding: 0 280px;
    background-color: #4086FF;
}

.header-container .header-content {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-content: center;
    margin: 0 auto;
    height: 100%;
    width: 100%;   
}


    /* Header content */
    .header-content .logo {
        cursor: pointer;
    }

    .header-content .menu-btn {
        cursor: pointer;
    }

    /* List Menu */
    .header-content .list-menu {
        cursor: pointer;
    }

    .active-menu-list {
        background-color: #FFA216;
    }

    .list-menu .menu-items {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;
        width: 97px;
        font-weight: 700;
        size: 16px;
        color: #ffffff;
        text-align: center;
    }

    .list-menu .menu-items:hover {
        background-color: #FFA216;
    }

    /* USER */
    .header-content .user{
        cursor: pointer;
    }

    .user .notification {
        margin-right: 36px;
    }

    .user .user-name span {
        font-weight: 700;
        size: 16px;
        color: #ffffff;
        text-align: center;
        margin-right: 18px;
    }



</style>
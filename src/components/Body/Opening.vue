<template>
    <div class="opening-container">
        <div class="opening-content">
            <img src="/public/assets/Body/Opening/banner.png" alt="">
        </div>
        <div class="opening-description">
            <div class="title">
                <span class="title_1">Tiến bộ mỗi ngày <span class="title_2">Cùng gia sư CoLearn</span></span>
            </div>
            <div class="list-text">
                <div class="text-items">
                    <div class="text-items_img">
                        <img src="/public/assets/Body/Opening/Icon1.png" alt="">
                    </div>
                    <span>Gia sư chất lượng</span>
                    <p>Đội ngũ gia sư CoLearn được tuyển chọn từ các trường đại học hàng đầu. Có kinh nghiệm và kỹ năng sư phạm</p>
                </div>
                <div class="text-items">
                    <div class="text-items_img">
                        <img src="/public/assets/Body/Opening/Icon2.png" alt="">
                    </div>
                    <span>Kho thư viện đa dạng</span>
                    <p>Tặng kho thư viện với hàng nghìn video bài giảng, tài liệu học tập và bộ đề trắc nghiệm không giới hạn. Giúp học sinh chủ động tự học hàng ngày</p>
                </div>
                <div class="text-items">
                    <div class="text-items_img">
                        <img src="/public/assets/Body/Opening/Icon3.png" alt="">
                    </div>
                    <span>Cá nhân hóa lộ trình học tập</span>
                    <p>Chương trình học được thiết kế riêng theo năng lực của mỗi học sinh và điều chỉnh theo sự tiến bộ của các em.</p>
                </div>
            </div>
        </div>

        
    </div>
</template>

<script>
export default {
    name: 'Opening',
    data () {
        return {
        
        }
    }
}
</script>

<style>



.opening-container {
    width: 100%;
    margin-top: 64px;
}

/* Content */
.opening-container .opening-content {
    
}

.opening-container .opening-content img {
    width: 100%;
}

/* Description */
.opening-container .opening-description {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 484px;
    margin-top: 46px;
    padding: 0 270px;
}

    .opening-description .title {
        font-size: 36px;
        text-align: center;
        font-family: 'Roboto Slab', serif;
    }


    /* List Text */
    .opening-description .list-text {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        margin-top: 61px;
    }

        .list-text .text-items {
            display: flex;
            flex-direction: column;
            width: 375px;
        }
        
        .text-items .text-items_img {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100px;
            height: 100px;
            background-image: url("/public/assets/Body/Opening/BG.png");
        }

        .text-items span {
            margin-top: 32px;
            margin-bottom: 20px;
            font-weight: 700;
            font-size: 24px;
        }

        .text-items p {
            font-weight: 400;
            font-size: 16px;
        }

</style>
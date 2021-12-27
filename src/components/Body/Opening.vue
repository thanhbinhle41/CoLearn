<template>
    <div class="opening-container">
        <div class="opening-options">
            <div class="options-list">
                <div class="options-item">Lớp học</div>
                <div class="options-item active">Gia sư 1 kèm 1</div>
            </div>
            <div class="video-btn">
                <img src="/public/assets/Body/Opening/video.png" alt="">
                <span>Lớp của tôi</span>
            </div>
        </div>
        <div class="opening-content">
            <img src="/public/assets/Body/Opening/banner.png" alt="">
            <div class="opening-title">
                <p>Gia sư CoLearn</p> 
                <p>Hỗ trợ mùa thi </p>
                <p>Nâng cao thành tích</p>
            </div>
            <div class="opening-btn">
                <span>Học gia sư ngay</span>
            </div>
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

@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@800&family=Mulish:ital,wght@0,400;0,700;0,800;0,900;1,400&family=Raleway:ital,wght@0,700;1,400;1,500&family=Roboto+Slab:wght@900&family=Roboto:wght@400;700&display=swap');

.opening-container {
    width: 100%;
    margin-top: 64px;
}

/* Options */
.opening-container .opening-options {
    display: flex;
    padding: 0 289px;
    justify-content: space-between;
}

    .opening-options .options-list {
        display: flex;
        align-items: center;
        cursor: pointer;
    }

        .options-list .options-item {
            font-size: 16px;
            font-weight: 400;
            margin-right: 50px;
        }

        .options-list .active {
            font-weight: 500;
            color: #FFA216;
            border-bottom: 4px solid #FFA216;
        }

    .opening-options .video-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 151px;
        height: 39px;
        background: #FFA216;
        border-radius: 19.5px;
        margin-bottom: 8px;
    }

    .opening-options .video-btn span {
        font-weight: 500;
        font-size: 16px;
        color: #fff;
        margin-left: 14px;
    }



/* Content */
.opening-container .opening-content {
    position: relative;
    cursor: pointer;
    
}

.opening-container .opening-content img {
    width: 100%;
}

    .opening-content .opening-title {
        position: absolute;
        top: 166px;
        left:270px;
    }

    .opening-content .opening-title p {
        font-family: 'Montserrat', sans-serif;
        font-weight: 800;
        font-size: 48px;
        color: #fff;
    }

    .opening-content .opening-btn {
        display: flex;
        align-items: center;
        justify-content: center;
        position: absolute;
        left: 273px;
        bottom: 120px;
        width: 238px;
        height: 68px;
        background: #FFA216;
        border-radius: 34px;
        cursor: pointer;
    }

    .opening-content .opening-btn span {
        font-family: 'Mulish', sans-serif;
        font-weight: 800;
        font-size: 24px;
        color: white;
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
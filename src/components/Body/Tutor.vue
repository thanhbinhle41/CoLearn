<template>
    <div class="tutor-container">
        <div class="tutor-title">
            <span class="title_1">Hệ thống gia sư <span class="title_2">CoLearn</span></span>
            <p>Đội ngũ gia sư chất lượng, 100% đến từ các trường đại học top 1, Có kỹ năng sư phạm <br> và ít nhất 2 năm kinh nghiệm gia sư.</p>
        </div>
        <div class="tutor-list">
            <div class="tutor-list-items">
                <img src="/public/assets/Body/Tutor/1.png" alt="">
                <div class="tutor-profile">
                    <span class='title_1'>Gia sư Trần Diệu Linh</span>
                    <p>Trường đại học Sư phạm Hà Nội <br>(Sư phạm Ngữ văn)</p>
                </div>
            </div>
            <div class="tutor-list-items">
                <img src="/public/assets/Body/Tutor/2.png" alt="">
                <div class="tutor-profile">
                    <span class='title_1'>Gia sư Đàm Ngọc Anh</span>
                    <p>Trường đại học Bách khoa Hà Nội <br>(Gia sư môn Toán)</p>
                </div>
            </div>
            <div class="tutor-list-items">
                <img src="/public/assets/Body/Tutor/3.png" alt="">
                <div class="tutor-profile">
                    <span class='title_1'>Gia sư Hoàng Văn Sinh</span>
                    <p>Học viện Kỹ thuật Quân sự <br>(Gia sư môn Hóa học)</p>
                </div>
            </div>
            <div class="tutor-list-items">
                <img src="/public/assets/Body/Tutor/4.png" alt="">
                <div class="tutor-profile">
                    <span class='title_1'>Gia sư Bùi Thị Trung Anh</span>
                    <p>Trường đại học Sư phạm Hà Nội <br>(Sư phạm Tiếng Anh)</p>
                </div>
            </div>
            <div class="tutor-list-items">
                <img src="/public/assets/Body/Tutor/5.png" alt="">
                <div class="tutor-profile">
                    <span class='title_1'>Gia sư Phạm Thị Thu Thảo</span>
                    <p>Trường đại học Dược Hà Nội <br> (Sư phạm môn Toán)</p>
                </div>
            </div>
        </div>
        <div class="banner">
            <img src="/public/assets/Body/Tutor/banner.png" alt="banner">
        </div>
    </div>
</template>

<script>
export default {
    name: "tutor",
    data() {
        return {
            
        }
    },
}
</script>

<style>
    .tutor-container {

    }

    /* Title */
    .tutor-container .tutor-title {
        padding-top: 57px;
        text-align: center;
    }
        .tutor-title span {
            font-weight: 900;
            font-family: 'Roboto Slab', serif;
            font-size: 36px;
        }

        .tutor-title p {
            color: #888888;
            font-size: 16px;
            line-height: 30px;
            margin-top: 13px;
        }

    /* Tutor list */
    .tutor-container .tutor-list {
        display: flex;
        padding: 0 310px;
        align-items: center;
        justify-content: space-between;
    }

        .tutor-list .tutor-list-items {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .tutor-list .tutor-list-items img {
            cursor: pointer;
        }

        .tutor-list-items .tutor-profile {
            text-align: center;
            margin-top: 24px;
        }

        .tutor-list-items .tutor-profile span {
            font-weight: 900;
            font-size: 18px;
            font-family: 'Roboto Slab', serif;
            cursor: pointer;
        }

        .tutor-list-items .tutor-profile p {
            font-weight: 400;
            font-size: 14px;
            color: #888888;
            line-height: 24px;
            margin-top: 8px;
        }

    /* Banner */
    .tutor-container .banner {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 90px;
        cursor: pointer;
    }

</style>
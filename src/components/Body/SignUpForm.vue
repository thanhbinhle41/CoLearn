<template>
    <div class="signUpForm-container">
        <div class="signUpForm-profile">
            <div class="profile-title">
                <span>Đăng ký nhận tư vấn</span>
                <span>Gia sư online 1 kèm 1</span>
                <p>Chắc kiến thức cơ bản - Chuẩn kiến thức nâng cao</p>
            </div>

            <div class="profile-input">
                <input type="text" placeholder="Họ và tên" class="name-input" required>
                <input type="tel" placeholder="Số điện thoại" class="name-input" required>
                <div class="d-flex">
                    <div class="options_input-form" style="margin-right: 24px;">
                        <input type="tel" placeholder="Lớp" class="options_input" required>
                        <div class='icon-down'>
                            <img src="/public/assets/Body/Form/Down.png" alt="">
                        </div>
                    </div>
                    <div class="options_input-form">
                        <input type="tel" placeholder="Môn học quan tâm" class="options_input" required>
                        <div class='icon-down'>
                            <img src="/public/assets/Body/Form/Down.png" alt="">
                        </div>
                    </div>
                </div>
                <textarea name="" id="" cols="30" rows="10" placeholder="Để lại lời nhắn cho chúng tôi" class="message-input"></textarea>
            </div>

            <div class="signUp-btn">
                <span>Đăng ký ngay</span>
            </div>
        </div>
            
        <div class="signUpForm-banner">
            <div class="banner-title title_1">
                <span class="banner-title-1">Ưu đãi tặng kèm</span>
                <span class="banner-title-2">1 lớp học gia sư </span>
                <span class="banner-title-2">Miễn phí đăng ký <span  class="banner-title-1">1 môn học</span> bất kỳ </span>
            </div>
            <div class="banner-description">
                <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Dạy tận tâm, chuẩn kiến thức</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Chủ động thời gian - Tiết kiệm chi phí</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Truy cập miễn phí kho thư viện bài giảng <br> độc quyền</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Cam kết tiến bộ sau 1 lộ trình</p>
                    </div>
            </div>
            <div class="banner-img">
                <img src="/public/assets/Body/Form/Person.png" alt="">
            </div>
        </div>

    </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,400;0,700;0,800;0,900;1,400&family=Raleway:ital,wght@0,700;1,400;1,500&family=Roboto+Slab:wght@900&family=Roboto:wght@400;700&display=swap');
    .signUpForm-container {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 705px;
        border-radius: 10px;
        margin-top: 130px;
    }

    .signUpForm-container .signUpForm-profile {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 690px;
        height: 100%;
        background: #003294;
        padding: 31px 97px 37px;
    }

        .signUpForm-profile .profile-title {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

            .signUpForm-profile .profile-title span {
                font-family: 'Mulish', sans-serif;
                font-weight: 800;
                font-size: 36px;
                text-transform: uppercase;
                color: white;
            }

            .signUpForm-profile .profile-title p {
                font-family: 'Raleway', sans-serif;
                font-size: 14px;
                font-style: italic;
                font-weight: 500;
                color: white;
                padding-top: 16px;
            }

        /* Input */
        .signUpForm-profile .profile-input {
            margin-top: 43px;
        }

            .profile-input .name-input {
                color: #A8A8A8;
                padding: 18px;
                border-radius: 8px;
                width: 496px;
                height: 56px;
                outline-width: 0;
                border: 0;
                margin-bottom: 24px;
            }

            .profile-input .options_input-form {
                position: relative;
                
                
            }

                .options_input-form .options_input {
                    padding: 18px;
                    width: 235px;
                    height: 56px;
                    background: #FFFFFF;
                    border-radius: 8px;
                    outline-width: 0;
                    border: 0;
                }

                .options_input-form .icon-down {
                    position: absolute;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    top: 24px;
                    right: 12px;
                }

            .profile-input .message-input {
                padding: 18px;
                margin-top: 24px;
                width: 496px;
                height: 121px;
                background: #FFFFFF;
                border-radius: 8px;
                outline-width: 0;
                border: 0;
            }

        /* Sign up btn */

        .signUpForm-profile .signUp-btn {
            display: flex;
            justify-content: center;
            align-items: center;

            width: 168px;
            height: 56px;
            margin-top: 24px;
            background: #FF9900;
            border-radius: 8px;
            color: white;
            font-size: 18px;
            cursor: pointer;
            font-family: 'Raleway', sans-serif;
            font-weight: 700;
        }

    /* End profile */

    .signUpForm-container .signUpForm-banner {
        position: relative;
        width: 690px;
        height: 100%;
        background: #F3F3F3;
        padding-left: 48px;
    }

        .signUpForm-banner .banner-title {
            display: flex;
            flex-direction: column;
            margin-top: 31px;
        }

            .banner-title .banner-title-1 {
                font-family: 'Mulish', sans-serif;
                font-weight: 800;
                font-size: 36px;
            }

            .banner-title .banner-title-2 {
                font-family: 'Mulish', sans-serif;
                font-weight: 500;
                font-size: 26px;
            }

        .signUpForm-banner .banner-description {
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-top: 32px;
        }   
        
        .banner-description .description-item {
            display: flex;
            margin-bottom: 17px;
        }

            .banner-description .description-item p {
                font-family: 'Mulish', sans-serif;
                font-weight: 400;
                font-size: 16px;
                padding-left: 20px;
                color: #003294;
            }

        .signUpForm-banner .banner-img {
            position: absolute;
            bottom: 0;
            right: 0;
        }


</style>
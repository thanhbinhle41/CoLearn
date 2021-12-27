<template>
    <footer class='footer'>
        <div style="padding-top: 22px">
            <img src="/public/assets/Footer/logo.png" alt="">
        </div>

        <div class="About">
            <div class="company-information">
                <p><span>Công ty chủ quản:</span> Công ty Cổ phần Đầu tư Phát triển Công nghệ Điện tử Viễn thông (Elcom Corp)</p>
                <p><span>Trụ sở chính:</span> Tòa nhà ELCOM, phố Duy Tân,quận ​Cầu Giấy,thành phố Hà Nội, Việt Nam</p>
                <p><span>Giấy chứng nhận ĐKKD:</span> số 0101435127 do Sở Kế hoạch & Đầu tư Thành phố Hà Nội.</p>
                <p>Cấp ngày 18/07/2003.</p>
                <p>Thay đổi lần thứ 24, ngày 28/05/2020</p>

                <img src="/public/assets/Footer/bct.png" alt="">

                <p style="margin-top: 66px;">© 2020 - Bản quyền thuộc về Công ty cổ phần Elcom</p>
            </div>

            <div class="information">
                <h5>THÔNG TIN</h5>
                <p>Giới thiệu</p>
                <p>Dịch vụ Colearn</p>
                <p>Điều khoản sử dụng</p>
                <p>Chính sách bảo mật</p>
                <p>Hướng dẫn sử dụng</p>
            </div>

            <div class="information">
                <h5>DỊCH VỤ</h5>
                <p>Hỏi bài</p>
                <p>Lớp học</p>
                <p>Thư viện CoLearn</p>
                <h5 style='margin-top: 16px;'>KẾT NỐI COLEARN</h5>
                <div>
                    <img src="/public/assets/Footer/youtube.png" alt="">
                    <img src="/public/assets/Footer/facebook.png" alt="" style="margin-left:16px;">
                </div>
            </div>

             <div class="information">
                <h5>HỖ TRỢ KHÁCH HÀNG</h5>
                <div class="d-flex">
                    <div style="margin-right: 18px;"><img src="/public/assets/Footer/Phone.png" alt=""></div>               
                    <p>Hotline: 1900866648</p>
                </div>
                <div class="d-flex">
                    <div style="margin-right: 18px;"><img src="/public/assets/Footer/Message.png" alt=""></div>               
                    <p>support@colearn.com.vn</p>
                </div>
                
                <h5 style='margin-top: 16px;'>TẢI ỨNG DỤNG COLEARN</h5>
                <div class="d-flex">
                    <div style="margin-right: 4px;"><img src="/public/assets/Footer/QR.png" alt=""></div>
                    <div class="d-flex flex-column">
                        <img src="/public/assets/Footer/Apple.png" alt="" style="margin-bottom: 4px">
                        <img src="/public/assets/Footer/GgPlay.png" alt="">
                    </div>
                </div>
                <p style="font-size: 10px;">Quét mã QR code để cài đặt </p>
            </div>


        </div>
        
        <div class="messenger-icon">
            <img src="/public/assets/Footer/messenger.png" alt="">
        </div>

        <div class="up-btn">
            <img src="/public/assets/Footer/Up.png" alt="">
        </div>
        
    </footer>
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
    .footer {
        position: relative;
        width: 100%;
        height: 475px;
        background: #F4F4F4;
        margin-top: 94px;
        padding-left: 280px;
        padding-right: 310px;
    }

    .footer .About {
        padding-top: 28px;
        display: flex;
        justify-content: space-between;
    }

        /* Company Information */

        .About .company-information {
            
        }

            .About .company-information p {
                font-size: 14px;
                font-family: 'Mulish', sans-serif;
                font-weight: 400;
                line-height: 35px;
            }

            .About .company-information p span {
                font-weight: 700;
            }

            .About .company-information img {
                margin-top: 14px;
            }

        /* Information */
        .About .information {
            display: flex;
            flex-direction: column;
        }

            .About .information h5 {
                font-weight: 900;
                font-size: 14px;
            }

            .About .information p {
                cursor: pointer;
                font-weight: 400;
                font-size: 14px;
                line-height: 27px;
                margin-bottom: 9px;
            }

    .footer .messenger-icon {
        position: absolute;
        right: 62px;
        top: 200px;
    }

    .footer .up-btn {
        display: flex;
        justify-content: center;
        align-items: center;
        position: absolute;
        background: #FFA216;
        border-radius: 10px;
        width: 36px;
        height: 36px;
        right: 77px;
        bottom: 53px;
    }


</style>
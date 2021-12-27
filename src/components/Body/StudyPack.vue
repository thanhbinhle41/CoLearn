<template>
    <div class="package-container">
        <div class="package-title">
            <span class="title_1" style="font-weight: 700;">Lựa chọn</span>
            <br>
            <span class="title_1" style="font-family: 'Roboto Slab', serif;">Chương trình học phù hợp</span>
        </div>
        <div class="package_price-container">
            <div class="package_price-item">
                <div class="icon-wrapper">
                    <div class="package_price-icon">
                        <img src="/public/assets/Body/Package Price/Work.png" alt="work">              
                    </div>
                </div>        

                <div class="price-title" style="margin-bottom: 70px;">
                    <h4>Gói trải nghiệm</h4>
                    <p>(4 buổi học)</p>
                </div>

                <div class="package_price-number">
                    <h3>Học phí:</h3>
                    <span>520.000 vnđ</span>
                </div>

                <div class="package_price-description">
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>4 buổi học gia sư 1 kèm 1</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Phù hợp để trải nghiệm dịch vụ</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Chi phí ban đầu thấp nhất</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Tặng kho thư viện bài giảng 1 tháng</p>
                    </div>
                </div>

                <div class="sign_up-btn">
                    <span>Đăng ký ngay</span>
                </div>
            </div>

            <div class="package_price-item">
                <div class="icon-wrapper">
                    <div class="package_price-icon">
                        <img src="/public/assets/Body/Package Price/Rocket.png" alt="work">              
                    </div>
                </div>        

                <div class="price-title">
                    <h4>Học kỳ bứt phá</h4>
                    <p>(24 buổi học - 3 tháng)</p>
                </div>

                <div class="d-flex justify-content-center align-items-center">
                    <div class="price-discount">
                        <img src="/public/assets/Body/Package Price/Discount.png" alt="">
                        <span>Giảm giá 10%</span>
                    </div>
                </div>
                

                <div class="package_price-number">
                    <h3>Học phí:</h3>
                    <span>2.810.000 vnđ</span>
                </div>

                <div class="package_price-description">
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>24 buổi học gia sư 1 kèm 1</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Lộ trình được điều chỉnh theo sự tiến bộ của học sinh</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Tặng kho thư viện bài giảng 6 tháng</p>
                    </div>
                </div>

                <div class="sign_up-btn">
                    <span>Đăng ký ngay</span>
                </div>
            </div>

            <div class="package_price-item">
                <div class="icon-wrapper">
                    <div class="package_price-icon">
                        <img src="/public/assets/Body/Package Price/Cup.png" alt="work">              
                    </div>
                </div>        

                <div class="price-title">
                    <h4>Năm học thành công </h4>
                    <p>(48 buổi học - 6 tháng)</p>
                </div>

                <div class="d-flex justify-content-center align-items-center">
                    <div class="price-discount">
                        <img src="/public/assets/Body/Package Price/Discount.png" alt="">
                        <span>Giảm giá 15%</span>
                    </div>
                </div>

                <div class="package_price-number">
                    <h3>Học phí:</h3>
                    <span>5.300.000 vnđ</span>
                </div>

                <div class="package_price-description">
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>48 buổi học gia sư 1 kèm 1</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Lộ trình được điều chỉnh theo sự tiến bộ của học sinh</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Học phí rẻ nhất</p>
                    </div>
                    <div class="description-item">
                        <div>
                            <img src="/public/assets/Body/Package Price/check.png" alt="check">
                        </div>
                        <p>Tặng kho thư viện bài giảng 12 tháng</p>
                    </div>
                </div>

                <div class="sign_up-btn">
                    <span>Đăng ký ngay</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Mulish:ital@1&family=Raleway:wght@700&family=Roboto+Slab:wght@900&family=Roboto:wght@400;700&display=swap');
    .package-container {
        position: relative;
        margin-top: 71px;
    }

    /* Title */
    .package-container .package-title {
        font-family: 'Roboto', sans-serif;
        text-align: center;
    }

        .package-title span {
            font-size: 36px;
        }

    /* Price */
    .package-container .package_price-container {
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-content: center;
        margin-top: 101px;
        padding: 0 300px;
    }

        .package_price-container .package_price-item {
            position: relative;
            background: #FFFFFF;
            box-shadow: 0px 4px 24px rgba(0, 0, 0, 0.25);
            border-radius: 14px;
            width: 388px;
            height: 550px;
        }

        .package_price-container .package_price-item:hover {
            transform: scale(1.1);
        }

            .package_price-item .icon-wrapper {
                position:absolute;
                top: -51px;
                left: 0;
                right: 0;
                margin: 0 auto;
                width: 102px;
            }

            .package_price-item .package_price-icon {
                display: flex;
                justify-content: center;
                align-items: center;
                width: 102px;
                height: 102px;
                border-radius: 50%;
                background: #FFFFFF;
                border: 1px solid #EFEFEF;
                box-sizing: border-box;
                box-shadow: 0px 4px 36px rgba(91, 91, 91, 0.1);
            }


            .package_price-item .price-title {
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                padding-top: 65px;
                
            }

                .package_price-item .price-title h4{
                    font-weight: 700;
                    font-size: 24px;
                }

                .package_price-item .price-title p{
                    font-weight: 400;
                    font-size: 16px;
                    color: #888888;
                }


            .package_price-item .price-discount {
                display: flex;
                flex-direction: row;
                justify-content: center;
                align-items: center;
                width: 179px;
                height: 40px;
                background: linear-gradient(175.24deg, #4086FF 1.92%, #3070FF 98.08%);
                border-radius: 24px;
                margin-top: 14px;
                margin-bottom: 20px;
            }

                .package_price-item .price-discount span {
                    font-family: 'Mulish', sans-serif;
                    font-size: 16px;
                    color: #fff;
                    padding-left: 16px;
                }


            .package_price-item .package_price-number {
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
            }

                .package_price-item .package_price-number h3 {
                    font-weight: 700;
                    font-size: 24px;
                    margin: 0;
                }

                .package_price-item .package_price-number span {
                    font-family: 'Roboto Slab', serif;
                    font-weight: 900;
                    font-size: 36px;
                }

            
            .package_price-item .package_price-description {
                display: flex;
                flex-direction: column;
                justify-content: center;
                margin-top: 42px;
            }

                .package_price-description .description-item {
                    display: flex;
                    flex-direction: row;
                    padding-left: 17px;
                    margin-bottom: 17px;
                }

                .package_price-description .description-item p {
                    font-weight: 400;
                    font-size: 16px;
                    padding-left: 20px;
                    color: #222222;
                }


            .package_price-item .sign_up-btn {
                position: absolute;
                left: 0;
                right: 0;
                bottom: -28px;
                margin: 0 auto;

                display: flex;
                justify-content: center;
                align-items: center;

                width: 188px;
                height: 56px;
                background: #FF9900;
                border-radius: 8px;
                cursor: pointer;
            }

                .package_price-item .sign_up-btn span {
                    color: white;
                    font-size: 18px;
                    font-weight: 700;
                    font-family: 'Raleway', sans-serif;
                }



</style>
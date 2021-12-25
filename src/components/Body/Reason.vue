<template>
  <div class="reason-container">
        <div class="reason-title">
            <span class="title_1">Vì sao nên chọn học</span>
            <span class="title_2">Gia sư 1 kèm 1 tại CoLearn</span>
        </div>
        <div class="reason-content">
            <img src="/public/assets/Body/Reason/girl.png" alt="" class="h-100">
            <div class="reason-list-text">
                <div class="list-text_items">
                    <div class="icon-wrapper">
                        <div class="icon">
                            <img src="/public/assets/Body/Reason/Book.png" alt="book">
                        </div>
                    </div>
                    
                    <div class="reason-text">
                        <span class="title_1">Giảm áp lực học tập với phiên học ngắn</span>
                        <p>Gia sư 1 kèm 1 CoLearn được thiết kế với thời lượng mỗi buổi học không quá dài. Giúp giảm áp lực học cho các em học sinh.</p>
                    </div>
                </div>
                <div class="list-text_items">
                    <div class="icon-wrapper">  
                        <div class="icon">
                            <img src="/public/assets/Body/Reason/Quality.png" alt="quality">
                        </div>
                    </div>
                    
                    <div class="reason-text">
                        <span class="title_1">Cam kết tiến bộ sau 1 lộ trình</span>
                        <p>Lộ trình học rõ ràng: Đánh giá đầu vào - học - hỏi - luyện - kiểm tra, giúp con tiến bộ trong học tập</p>
                    </div>
                </div>
                <div class="list-text_items">
                    <div class="icon-wrapper">
                        <div class="icon">
                            <img src="/public/assets/Body/Reason/User.png" alt="Friends">
                        </div>
                    </div>

                    <div class="reason-text">
                        <span class="title_1">Cộng đồng gia sư - học sinh giỏi hỗ trợ giải đáp</span>
                        <p>Với phương châm THẦY GIỎI _ TRÒ GIỎI. Cộng đồng hỏi bài CoLearn luôn hỗ trợ giải đáp mọi lúc mọi nơi khi học sinh gặp bài khó</p>
                    </div>
                </div>
                <div class="list-text_items m-0">
                    <div class="icon-wrapper">
                        <div class="icon">
                            <img src="/public/assets/Body/Reason/Clock.png" alt="Clock">
                        </div>
                    </div>
                    <div class="reason-text">
                        <span class="title_1">Chủ động thời gian - Tiết kiệm chi phí</span>
                        <p>Học gia sư 1 kèm 1 ngay tại nhà qua hệ thống học trực tuyến của Colearn sẽ giúp học sinh tiết kiệm thời gian, chi phí học và còn đảm bảo hơn trong mùa dịch</p>
                    </div>
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

.reason-container {
    width: 100%;
    height: 722px;
    background-color: #F8F8F8;
    padding: 0 270px;
}

/* Title */

.reason-container .reason-title {
    display: flex;
    flex-direction: column;

    width: 100%;
    padding-top: 61px;
    margin-bottom: 45px;
    text-align: center;

    font-size: 36px;
    text-align: center;
    font-family: 'Roboto Slab', serif;
    font-weight: 900;
}

/* Content */
.reason-container .reason-content {
    display: flex;
    flex-direction: row;
}

    .reason-content .reason-list-text {
        padding-left: 24px;
    }

        .reason-list-text .list-text_items {
            display: flex;
            flex-direction: row;
            margin-bottom: 45px;
        }

        .reason-list-text .list-text_items .icon {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 56px;
            height: 56px;
            border-radius: 50%;
            background-color: white;
            margin-right: 32px;
            box-shadow: 0px 4px 16px rgba(0, 0, 0, 0.1);
        }

        .list-text_items .reason-text {
            position: relative;
        }

            .reason-text span {
                margin-bottom: 10px;

                font-weight: 700;
                font-size: 18px;
            }

            .reason-text p {
                font-weight: 400;
                font-size: 14px;
                margin-top: 10px;
            }

</style>
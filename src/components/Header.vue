<template>
    <div class="header-section">
        <div class="container d-flex justify-content-end">
            <div class="content">
                <h2>エン <br />スタ</h2>
                <div class="button-grp">
                    <div class="left">
                        <span>ログイン</span>
                    </div>
                    <div class="right">
                        <span>新規登録</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.header-section {
    width: 100%;
    min-height: 80px;
    position: fixed;
    display: flex;
    align-items: center;
    z-index: 10;
    padding: 15px 0;
}

.header-section h2 {
    font-family: 'A P-OTF LapisMelt Min2';
    font-style: normal;
    font-weight: 700;
    font-size: 28.1446px;
    line-height: 115%;
}

.header-section .content {
    display: flex;
    align-items: center;
    position: relative;
    right: -70px;
}

.header-section .button-grp {
    width: 201px;
    height: 30px;
    margin-left: 19px;
    background: rgba(255, 255, 255, 0.5);
    display: flex;
}

.header-section .button-grp .left,
.header-section .button-grp .right {
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    border-left: 1px solid rgba(0, 210, 255, 1);
}

.header-section .button-grp .right {
    border-left: 1px solid rgba(0, 210, 255, 1);
    border-right: 1px solid rgba(0, 210, 255, 1);
}

.header-section .button-grp span {
    font-family: 'Yu Gothic';
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 175%;
    background: linear-gradient(270deg, #00D2FF -20.61%, #3A7BD5 93.33%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-shadow: 0px 0px 20px rgba(255, 255, 255, 0.5);
}

@media (max-width:1200px) {
    .header-section .content {
        right: 0;
    }
}

@media (max-width:600px) {
    .header-section .content {
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        position: relative;
        right: 0;
    }
}
</style>
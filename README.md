# CHZZK_kane_0do_CSS
[치지직] 파트너 스트리머 케인 님께서 사용하시는 영도 사용자 지정 CSS<br/>
<br/>
OBS→영상 후원 알림 소스의 속성<br/>
너비: 1280<br/>
높이: 950<br/>
사용자 지정 CSS에 적용<br/>

```css
* {
    margin: 0 /* 55번째 수정*/ !important;
    padding: 0 !important;
    box-sizing:  border-box !important;
}

html, body {
    width: 100%;
    height: 100%;
    overflow: hidden;
    background-color: rgba(0, 0, 0, 0) !important;
}

[class*="overlay_donation_alarm"] {
    position: relative !important;
    width: 1280px;
    height: 720px;
}

[class*="overlay_donation_alarm"] * {
    pointer-events: none;
}

iframe[src*="youtube-nocookie.com"],
iframe[src*="/embed-clip-donation/"] {
    position: absolute !important;
    top: 0 !important;
    left: 0 !important;
    width: 1280px !important;
    height: 720px !important;
    border: none !important;
    pointer-events: auto !important;
}

[class*="overlay_donation_contents"] {
    position: absolute !important;
    top: 720px !important;
    left: 0 !important;
    width: 100% !important;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    padding: 10px 30px 20px 30px;
}

[class*="overlay_donation_description"],
[class*="overlay_donation_video_title"] {
    width: 100% !important;
    font-size: 36px !important;
    line-height: 56px !important;
    font-weight: bold !important;
    color: white !important;
    text-align: center !important;
    word-break: keep-all;
}

[class*="overlay_donation_description"],
[class*="overlay_donation_text"] span,
[class*="overlay_donation_video_title"] {
    text-shadow: 0 0 7px black, 0 0 12px black !important;
}

[class*="overlay_donation_icon_cheese"],
[class*="badge_container"] img,
[class*="live_chatting_username_icon"] img {
    height: 48px !important;
    width: 48px !important;
    position: relative;
    top: 2px;
}

[class*="live_chatting_username_wrapper"],
[class*="live_chatting_username_container"] {
    display: inline-flex !important;
    align-items: center !important;
}

[class*="overlay_donation_description"] {
    padding: 0 20px !important;
}

[class*="overlay_donation_text"] {
    width: 100% !important;
    font-size: 40px !important;
    line-height: 50px !important;
    font-weight: normal !important;
    color: white !important;
    padding: 15px 10px 5px 10px !important;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
}

[class*="live_chatting_username_wrapper"] {
    gap: 6px !important;
    margin-right: 5px !important;
}

[class*="overlay_donation_video_title"] {
    padding: 20px 30px !important;
}

[class*="overlay_donation_money"] {
    margin-right: 5px !important;
}
```

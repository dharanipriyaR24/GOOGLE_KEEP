<template>
  <body>
<app-navbar _ngcontent-hlx-c12="" _nghost-hlx-c9="">
  <section _ngcontent-hlx-c9="" class="main-container">
    <div _ngcontent-hlx-c9="" class="navbar">
      <div _ngcontent-hlx-c9="" class="first-col">
        <div _ngcontent-hlx-c9="" class="pic-container H">
          <img _ngcontent-hlx-c9="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/menu.svg" alt="menu" class="menu-icon">
        </div>
         
          <div _ngcontent-hlx-c9="" class="keep-img">
<img _ngcontent-hlx-c9="" src="https://google-keep-clone-lovat.vercel.app/assets/images/keep.png" width="40" alt="keep">
          </div>
<div _ngcontent-hlx-c9="">
  <span _ngcontent-hlx-c9="" class="text">Keep</span></div></div>
  <div _ngcontent-hlx-c9="" class="sec-col">
    <div _ngcontent-hlx-c9="" class="form-container">
      <form _ngcontent-hlx-c9="" class="form">
        <div _ngcontent-hlx-c9="" class="input-container">
          <input _ngcontent-hlx-c9="" autocomplete="off" placeholder="Search" value="" type="text" class="input"></div>
  
      </form></div>
              <div _ngcontent-hlx-c9="" class="btns-container">
                <div _ngcontent-hlx-c9="" data-pop="Search" class="search H pop"></div>
               <div _ngcontent-hlx-c9="" data-pop="Refresh" class="refresh H pop"></div>
                <div _ngcontent-hlx-c9="" data-pop="List view" class="view H pop" ></div>
                <div _ngcontent-hlx-c9="" data-pop="Settings" class="settings H pop disabled">

                </div></div></div>
                <div _ngcontent-hlx-c9="" class="th-col"><div _ngcontent-hlx-c9="" data-pop="Google Apps" class="apps H disabled pop">

                </div>
                <div _ngcontent-hlx-c9="" class="user-pic-container">
<img _ngcontent-hlx-c9="" src="https://lh3.googleusercontent.com/ogw/AOh-ky0S9GP6AlzBwHrovPZcLRH0CIOynVaWfUkHnBPYu5M=s32-c-mo"  alt="user-pic" class="user-pic">
</div></div></div>
</section></app-navbar>
<section _ngcontent-hlx-c12="" class="main-section">
  <div _ngcontent-hlx-c12="" class="d-flex"><div _ngcontent-hlx-c12="">
    <app-sidenav _ngcontent-hlx-c12="" _nghost-hlx-c8="">
      <div _ngcontent-hlx-c8="" sidebar="" class="main-sidebar">
        <div _ngcontent-hlx-c8="">
          <div _ngcontent-hlx-c8="" routerlink="/" class="item" tabindex="0">
            <img _ngcontent-hlx-c8="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/lamp.svg" alt="lamp" class="pic"><span _ngcontent-hlx-c8="" class="text">Notes</span></div><div _ngcontent-hlx-c8="" class="item disabled">
              <img _ngcontent-hlx-c8="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/reminder.svg" alt="reminder" class="pic"><span _ngcontent-hlx-c8="" class="text">Reminders</span></div>
              <div _ngcontent-hlx-c8="" class="item">
                <img _ngcontent-hlx-c8="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/pen.svg" alt="pen" class="pic"><span _ngcontent-hlx-c8="" class="text">Edit labels</span></div>
                <div _ngcontent-hlx-c8="" routerlink="/archive" class="item" tabindex="0">
                  <img _ngcontent-hlx-c8="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/archive.svg" alt="archive" class="pic">
                  <span _ngcontent-hlx-c8="" class="text">Archive</span>
                </div>
                <div _ngcontent-hlx-c8="" routerlink="/trash" class="item" tabindex="0">
                  <img _ngcontent-hlx-c8="" src="https://google-keep-clone-lovat.vercel.app/assets/images/svg/trash.svg" alt="trash" class="pic">
                  <span _ngcontent-hlx-c8="" class="text">Trash</span>
                </div></div></div>
          <div _ngcontent-hlx-c8="" class="modal-container" style="display: none;">
          <div _ngcontent-hlx-c8="" class="modal"><div _ngcontent-hlx-c8="" class="label-modal-main">
            <div _ngcontent-hlx-c8="" class="header"><p _ngcontent-hlx-c8="">Edit labels</p>
            <div _ngcontent-hlx-c8="" class="input-container"><div _ngcontent-hlx-c8="" class="plus-icon H"></div>
            <input _ngcontent-hlx-c8="" type="text" placeholder="Create new label" maxlength="50">
            <div _ngcontent-hlx-c8="" class="check-icon H" style="display: none;"></div></div>
            <div _ngcontent-hlx-c8="" hidden="" class="error">Label already exists</div></div><div _ngcontent-hlx-c8="" class="footer">
              <div _ngcontent-hlx-c8="" type="submit" tabindex="0">Done</div>
            </div></div></div></div></app-sidenav></div>
            <div _ngcontent-hlx-c12="" class="w-100 padding">
              <app-input _ngcontent-hlx-c12="" _nghost-hlx-c10="">
                <div _ngcontent-hlx-c10="" class="main-container">
              <div _ngcontent-hlx-c10="" class="placeholder">
                <input _ngcontent-hlx-c10=""  onclick="openGrid('expd1');" placeholder="Take a note…" type="text" class="input">
              <div _ngcontent-hlx-c10="" data-pop="New list" class="check H pop"></div>
              <div _ngcontent-hlx-c10="" data-pop="New note with drawing" class="paint H disabled pop"></div>
              <div _ngcontent-hlx-c10="" data-pop="New note with image" class="picture H disabled"></div></div>
              <div _ngcontent-hlx-c10="" hidden="" class="note-main">
                <div _ngcontent-hlx-c10="" class="note-container">
                <div _ngcontent-hlx-c10="" class="note-title ph"> Title</div>
                <div _ngcontent-hlx-c10="" contenteditable="true" spellcheck="true" class="note-title"></div>
                <div _ngcontent-hlx-c10="" class="note-body ph"><b>Take a note…</b></div>
                <div _ngcontent-hlx-c10="" contenteditable="true" spellcheck="true" class="note-body"></div>
                <div _ngcontent-hlx-c10="" class="labels-container"></div></div>
                <div _ngcontent-hlx-c10="" data-pinned="false" class="pin-icon H pop" data-pop="Pin note"></div>
                <div _ngcontent-hlx-c10="" class="icons-container">
                  <div _ngcontent-hlx-c10="" class="icons">
                    <div _ngcontent-hlx-c10="" data-pop="Remind me" class="alarm H disabled pop"></div>
                    <div _ngcontent-hlx-c10="" data-pop="Collaborator" class="colab H disabled pop"></div>
                  <div _ngcontent-hlx-c10="" data-pop="Background Options" class="color H pop"></div>
                  <div _ngcontent-hlx-c10="" data-pop="Add image" class="image H disabled pop"></div>
                  <div _ngcontent-hlx-c10="" data-pop="Archive" class="archive H pop"></div>
                  <div _ngcontent-hlx-c10="" data-pop="More" class="more H pop"></div>
                  <div _ngcontent-hlx-c10="" data-pop="Undo" class="undo disabled pop"></div>
                  <div _ngcontent-hlx-c10="" class="undo r disabled"></div></div>
                  <div _ngcontent-hlx-c10="" class="close-btn"> Close </div></div></div></div>
                  <div _ngcontent-hlx-c10="" data-tooltip="true" data-is-tooltip-open="false" class="moreMenu">
                    <div _ngcontent-hlx-c10="" hidden=""> Delete note </div>
                  </div>
                  <div _ngcontent-hlx-c10="" data-tooltip="true" data-is-tooltip-open="false" class="colorMenu">
                    <div _ngcontent-hlx-c10="" class="first-row">
                      <div _ngcontent-hlx-c10="" class="nocolor" data-bg-color="_"></div>
                      <div _ngcontent-hlx-c10="" data-bg-color="blue" style="background-color: rgb(45, 85, 94);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="brown" style="background-color: rgb(68, 47, 25);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="darkblue" style="background-color: rgb(30, 58, 95);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="gray" style="background-color: rgb(60, 63, 67);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="green" style="background-color: rgb(52, 89, 32);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="orange" style="background-color: rgb(97, 74, 25);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="pink" style="background-color: rgb(91, 34, 69);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="purple" style="background-color: rgb(66, 39, 94);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="red" style="background-color: rgb(92, 43, 41);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="teal" style="background-color: rgb(22, 80, 75);"></div>
                    <div _ngcontent-hlx-c10="" data-bg-color="yellow" style="background-color: rgb(99, 93, 25);"></div></div>
                    <div _ngcontent-hlx-c10="" class="second-row">
                      <div _ngcontent-hlx-c10="" class="noimage" data-bg-image="i0" style="background-image: url(&quot;&quot;);"></div>
                      <div _ngcontent-hlx-c10="" data-bg-image="i1" style="background-image: url(&quot;/assets/images/backgrounds/image-1_ph.svg&quot;);"></div>
                      <div _ngcontent-hlx-c10="" data-bg-image="i2" style="background-image: url(&quot;/assets/images/backgrounds/image-2_ph.svg&quot;);"></div>
                      <div _ngcontent-hlx-c10="" data-bg-image="i3" style="background-image: url(&quot;/assets/images/backgrounds/image-3_ph.svg&quot;);"></div>
                      <div _ngcontent-hlx-c10="" data-bg-image="i4" style="background-image: url(&quot;/assets/images/backgrounds/image-4_ph.svg&quot;);"></div>
                      <div _ngcontent-hlx-c10="" data-bg-image="i5" style="background-image: url(&quot;/assets/images/backgrounds/image-5_ph.svg&quot;);"></div></div></div>
                      <div _ngcontent-hlx-c10="" data-tooltip="true" data-is-tooltip-open="false" class="labelMenu"><div _ngcontent-hlx-c10="" class="title">Label note</div>
                      <div _ngcontent-hlx-c10="" class="search">
                        <input _ngcontent-hlx-c10="" type="text" maxlength="50" placeholder="Enter label name">
                        <div _ngcontent-hlx-c10="" class="search-icon"></div></div>
                        <div _ngcontent-hlx-c10="" class="label-list-container"></div></div></app-input>
                        <app-notes _ngcontent-hlx-c12="" _nghost-hlx-c11="">
                          <section _ngcontent-hlx-c11="">
                            <section _ngcontent-hlx-c11="" class="main-container">
                              <div _ngcontent-hlx-c11="" class="pb-80" hidden="">
                            <p _ngcontent-hlx-c11="" _title="">pinned</p>
                            <div _ngcontent-hlx-c11="" style="position: relative;"></div></div>
                            <div _ngcontent-hlx-c11="" hidden=""><p _ngcontent-hlx-c11="" _title="">other</p>
                              <div _ngcontent-hlx-c11="" style="position: relative;"></div></div></section></section>
                              <section _ngcontent-hlx-c11=""><div _ngcontent-hlx-c11="" class="no-notes">
                                <div _ngcontent-hlx-c11="" class="image"></div><div _ngcontent-hlx-c11="">
                                  <span _ngcontent-hlx-c11="" class="text">Notes you trash appear here</span></div></div></section>
                                  <div _ngcontent-hlx-c11="" class="modal-container"><div _ngcontent-hlx-c11="" class="modal"></div></div>
                                  <div _ngcontent-hlx-c11="" data-tooltip="true" data-is-tooltip-open="false" class="moreMenu">
                                    <div _ngcontent-hlx-c11="">Delete note</div>
                                    <div _ngcontent-hlx-c11="">Add label </div>
                                    <div _ngcontent-hlx-c11="">Make a copy</div></div>
                                    <div _ngcontent-hlx-c11="" data-tooltip="true" data-is-tooltip-open="false" class="colorMenu">
                                      <div _ngcontent-hlx-c11="" class="first-row">
                                      <div _ngcontent-hlx-c11="" class="nocolor" data-bg-color="_"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="blue" style="background-color: rgb(45, 85, 94);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="brown" style="background-color: rgb(68, 47, 25);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="darkblue" style="background-color: rgb(30, 58, 95);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="gray" style="background-color: rgb(60, 63, 67);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="green" style="background-color: rgb(52, 89, 32);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="orange" style="background-color: rgb(97, 74, 25);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="pink" style="background-color: rgb(91, 34, 69);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="purple" style="background-color: rgb(66, 39, 94);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="red" style="background-color: rgb(92, 43, 41);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="teal" style="background-color: rgb(22, 80, 75);"></div>
            <div _ngcontent-hlx-c11="" data-bg-color="yellow" style="background-color: rgb(99, 93, 25);"></div>
            </div>
            <div _ngcontent-hlx-c11="" class="second-row">
              
            <div _ngcontent-hlx-c11="" class="noimage" data-bg-image="i0" style="background-image: url(&quot;&quot;);"></div>
              <div _ngcontent-hlx-c11="" data-bg-image="i1" style="background-image: url(https://cdn-icons-png.flaticon.com/128/8901/8901324.png);"></div>
              <div _ngcontent-hlx-c11="" data-bg-image="i2" style="background-image: url(https://cdn-icons-png.flaticon.com/128/3394/3394388.png);"></div>
              <div _ngcontent-hlx-c11="" data-bg-image="i3" style="background-image: url(&quot;/assets/images/backgrounds/image-3_ph.svg&quot;);"></div>
              <div _ngcontent-hlx-c11="" data-bg-image="i4" style="background-image: url(&quot;/assets/images/backgrounds/image-4_ph.svg&quot;);"></div>
              <div _ngcontent-hlx-c11="" data-bg-image="i5" style="background-image: url(&quot;/assets/images/backgrounds/image-5_ph.svg&quot;);"></div></div></div>
              <div _ngcontent-hlx-c11="" data-tooltip="true" data-is-tooltip-open="false" class="labelMenu"><div _ngcontent-hlx-c11="" class="title">Label note</div>
              <div _ngcontent-hlx-c11="" class="search">
                <input _ngcontent-hlx-c11="" type="text" maxlength="50" placeholder="Enter label name"><div _ngcontent-hlx-c11="" class="search-icon"></div></div>
                <div _ngcontent-hlx-c11="" class="label-list-container"></div></div>
                </app-notes></div></div> <br>
                <br>
                <br>
                <br> <br>
                <br>
                <br>
                <br>
                </section>
                </body>
              
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.main-container[_ngcontent-hlx-c9] {
    padding: 8px;
    box-shadow: inset 0 -1px #5f6368;
}
.main-section[_ngcontent-hlx-c12] {
    padding-top: 8px;
}
.main-container[_ngcontent-hlx-c9][_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] {
    display: flex;
    align-items: center!important;
    justify-content: space-between!important;
}
main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] {
    display: flex;
    align-items: center!important;
    justify-content: space-between!important;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .first-col[_ngcontent-hlx-c9] {
    min-width: 232px;
    display: flex;
    align-items: center;
    height: 48px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] {
    padding-left: 10px;
    padding-right: 30px;
    width: 100%;
}
main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] {
    display: flex;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] {
    display: flex;
    justify-content: flex-end;
    width: 100%;
    align-items: center;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] {
    display: flex;
    justify-content: flex-end;
    width: 100%;
    align-items: center;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .user-pic-container[_ngcontent-hlx-c9] {
    padding: 4px 6px;
    display: inline-block;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .input-container[_ngcontent-hlx-c9] .input[_ngcontent-hlx-c9] {
    color: #ffffffde;
    background: transparent;
    font-size: 16px;
    font-family: "Google Sans Light 2";
    height: 46px;
    width: 100%;
    border: 0;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] {
    background: rgba(241,243,244,.24);
    max-width: 722px;
    border-radius: 8px;
    border: 1px solid transparent;
    position: relative;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .input-container[_ngcontent-hlx-c9] {
    margin-left: 54px;
    margin-right: 49px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .refresh[_ngcontent-hlx-c9]
 {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/refresh.svg);
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .input-container[_ngcontent-hlx-c9] .input[_ngcontent-hlx-c9] {
    color: #ffffffde;
    background: transparent;
    font-size: 16px;
    font-family: "Google Sans Light 2";
    height: 46px;
    width: 100%;
    border: 0;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .btn[_ngcontent-hlx-c9] {
    width: 56px;
    height: 46px;
    background: none;
    border: none;
    position: absolute;
    top: 0;
    right: 0;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .first-col[_ngcontent-hlx-c9] .text[_ngcontent-hlx-c9] {
    color: #ffffffde;
    font-family: Product Sans;
    font-size: 22px;
    vertical-align: middle;
    top: 0.5px;
    line-height: 24px;
    padding-left: 8px;
    position: relative;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .pic[_ngcontent-hlx-c9] {
    padding: 8px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .btn.left[_ngcontent-hlx-c9] {
    left: 0;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] {
    padding-left: 10px;
    padding-right: 30px;
    width: 100%;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .form-container[_ngcontent-hlx-c9] .form[_ngcontent-hlx-c9] .btn[_ngcontent-hlx-c9] {
    width: 56px;
    height: 46px;
    background: none;
    border: none;
    position: absolute;
    top: 0;
    right: 0;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] {
    display: flex;
    justify-content: flex-end;
    width: 100%;
    align-items: center;
}
.d-flex {
    display: flex!important;
}
.padding[_ngcontent-hlx-c12] {
    padding: 0 10px;
}
.main-sidebar[_ngcontent-hlx-c8] .item[_ngcontent-hlx-c8] .pic[_ngcontent-hlx-c8] {
    opacity: .54;
    padding: 0 12px;
}
.main-sidebar[_ngcontent-hlx-c8] .item[_ngcontent-hlx-c8] .text[_ngcontent-hlx-c8] {
    padding-left: 2px;
    margin-left: 20px;
    overflow: hidden!important;
    text-overflow: ellipsis;
    white-space: nowrap;
}
.w-100 {
    width: 100%!important;
}
.main-container[_ngcontent-hlx-c10] {
    margin: 24px auto 16px;
    max-width: 600px;
    width: 100%;
    box-shadow: 0 1px 2px #0009, 0 2px 6px 2px #0000004d;
    position: relative;
}
.settings H pop disabled:hover{
    background: orange;
}
.refresh H pop{
  height: 48px;
    width: 48px;
    background-size: 24px 24px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
    transition: opacity .218s linear;
    position: relative;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .refresh[_ngcontent-hlx-c9], .main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .view[_ngcontent-hlx-c9], .main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .settings[_ngcontent-hlx-c9], .main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .search[_ngcontent-hlx-c9], .main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .apps[_ngcontent-hlx-c9] {
    height: 48px;
    width: 48px;
    background-size: 24px 24px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
    transition: opacity .218s linear;
    position: relative;
  }
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .view[_ngcontent-hlx-c9] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/view.svg);
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .settings[_ngcontent-hlx-c9] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/settings.svg);
}

.no-notes[_ngcontent-hlx-c11] .image[_ngcontent-hlx-c11] {
    background-size: 120px 120px;
    height: 120px;
    width: 120px;
    margin: 20px;
    opacity: .1;
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/no-notes.svg);
}
.main-container[_ngcontent-hlx-c11] {
    margin-top: 45px;
    margin-bottom: 45px;
}
style attribute {
    --note-width: 240px;
}
.main-sidebar[_ngcontent-hlx-c8] .item[_ngcontent-hlx-c8] {
    box-sizing: border-box;
    border: 1px solid transparent;
    border-radius: 0 25px 25px 0;
    color: #e8eaed;
    display: flex;
    align-items: center;
    letter-spacing: .01785714em;
    font-family: Google Sans,Roboto,Arial,sans-serif;
    font-size: .875rem;
    font-weight: 500;
    line-height: 1.25rem;
    width: 100%;
    height: 48px;
    overflow: hidden;
    cursor: pointer;
    padding-left: 12px;
    transition: all .08s;
}
.main-sidebar[_ngcontent-hlx-c8] {
    display: flex;
    flex-direction: column;
    width: 280px;
    transition: width .08s;
}
.placeholder[_ngcontent-hlx-c10] .input[_ngcontent-hlx-c10] {
    padding: 21px 6px 11px 16px;
    font-family: "Google Sans Light 2";
    height: 46px;
    width: 100%;
    background-color: #202124;
    border: 1px solid #5f6368;
    border-radius: 8px;
}
*, *:before, *:after {
    box-sizing: border-box;
}
input[type="text" i] {
    padding: 1px 2px;
}
.menu-icon:hover , .refresh H pop:hover, .view H pop:hover{
    background-color: orange;

}
input {
    writing-mode: horizontal-tb !important;
    text-rendering: auto;
    color: fieldtext;
    letter-spacing: normal;
    word-spacing: normal;
    line-height: normal;
    text-transform: none;
    text-indent: 0px;
    text-shadow: none;
    display: inline-block;
    text-align: start;
    appearance: auto;
    -webkit-rtl-ordering: logical;
    cursor: text;
    background-color: field;
    margin: 0em;
    padding: 1px 2px;
    border-width: 2px;
    border-style: inset;
    border-color: -internal-light-dark(rgb(118, 118, 118), rgb(133, 133, 133));
    border-image: initial;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] {
    display: flex;
}
.placeholder[_ngcontent-hlx-c10] .pop.picture[_ngcontent-hlx-c10]:before, .placeholder[_ngcontent-hlx-c10] .pop.paint[_ngcontent-hlx-c10]:before, .placeholder[_ngcontent-hlx-c10] .pop.check[_ngcontent-hlx-c10]:before {
    top: 45px;
}
*::-webkit-scrollbar {
    height: 16px;
    overflow: visible;
    width: 16px;
}
*::-webkit-scrollbar-thumb {
    background-color: #ffffff4d;
    background-clip: padding-box;
    border: solid transparent;
    border-width: 1px 1px 1px 6px;
    box-shadow: inset 1px 1px #0000001a, inset 0 -1px #00000012;
}
*::-webkit-scrollbar-track {
    background-clip: padding-box;
    border: solid transparent;
    border-width: 0 0 0 4px;
}
*::-webkit-scrollbar-track {
    background: transparent;
}
.placeholder[_ngcontent-hlx-c10] .picture[_ngcontent-hlx-c10],
 .placeholder[_ngcontent-hlx-c10] .paint[_ngcontent-hlx-c10], 
 .placeholder[_ngcontent-hlx-c10] .check[_ngcontent-hlx-c10] {
    height: 46px;
    position: absolute;
    top: 1px;
    width: 46px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
}
.placeholder[_ngcontent-hlx-c10] .check[_ngcontent-hlx-c10] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/check.svg);
    right: 121px;
}
.placeholder[_ngcontent-hlx-c10] .paint[_ngcontent-hlx-c10] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/paint.svg);
    right: 67px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .sec-col[_ngcontent-hlx-c9] .btns-container[_ngcontent-hlx-c9] .view[_ngcontent-hlx-c9]
{
  height: 48px;
    width: 48px;
    background-size: 24px 24px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
    transition: opacity .218s linear;
    position: relative;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] {
    display: flex;
    align-items: center;
    height: 48px;
    padding: 0 4px 0 28px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .user-pic-container[_ngcontent-hlx-c9] {
    padding: 4px 6px;
    display: inline-block;
}
.placeholder[_ngcontent-hlx-c10] .picture[_ngcontent-hlx-c10], .placeholder[_ngcontent-hlx-c10] .paint[_ngcontent-hlx-c10], .placeholder[_ngcontent-hlx-c10] .check[_ngcontent-hlx-c10] 
{
    height: 46px;
    position: absolute;
    top: 1px;
    width: 46px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .apps[_ngcontent-hlx-c9] {
    height: 48px;
    width: 48px;
    background-size: 24px 24px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
    transition: opacity .218s linear;
    position: relative;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .apps[_ngcontent-hlx-c9] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/apps.svg);
    position: relative;
    right: 2px;
}
.main-container[_ngcontent-hlx-c9] .navbar[_ngcontent-hlx-c9] .th-col[_ngcontent-hlx-c9] .user-pic-container[_ngcontent-hlx-c9] .user-pic[_ngcontent-hlx-c9] {
    border-radius: 50%;
    height: 32px;
    width: 32px;
    margin-bottom: 1px;
}
.no-notes[_ngcontent-hlx-c11] {
    margin-top: 20vh;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
}
[data-tooltip=true].labelMenu {
    width: 225px;
    padding-top: 11px;
    background-color: #2d2e30;
}
[data-tooltip=true].labelMenu .search input {
    padding: 2px 22px 2px 2px;
    width: 100%;
    background-color: transparent;
    border: none;
    border-bottom: 1px solid transparent;
    box-shadow: none;
    color: #e8eaed;
    font-size: 13px;
    font-family: Roboto,arial,sans-serif;
    height: 25px;
    outline: none;
}
[data-tooltip=true].labelMenu .search .search-icon {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/search.svg);
    background-size: 14px 18px;
    height: 18px;
    width: 18px;
    opacity: .35;
    background-repeat: no-repeat;
}
[data-tooltip=true].colorMenu .first-row {
    display: flex;
}
.no-notes[_ngcontent-hlx-c11] .text[_ngcontent-hlx-c11] {
    color: #9aa0a6;
    font-family: "Google Sans Light 1";
    font-size: 1.375rem;
    font-weight: 400;
    letter-spacing: 0;
    line-height: 1.75rem;
}
[data-tooltip=true].colorMenu .first-row div {
    border-radius: 50%;
    width: 32px;
    height: 32px;
    margin: 2px;
    border: 2px solid transparent;
    text-align: center;
}
[data-tooltip=true].colorMenu {
    flex-direction: column;
    align-items: center;
    padding: 8px 9px 3px;
    align-items: flex-start;
}
[data-tooltip=true].labelMenu .title {
    font-size: 14px;
    padding: 0 12px;
    font-family: Roboto,arial,sans-serif;
}
[data-tooltip=true].labelMenu .search .search-icon {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/search.svg);
    background-size: 14px 18px;
    height: 18px;
    width: 18px;
    opacity: .35;
    background-repeat: no-repeat;
}

[data-tooltip=true].moreMenu div {
    border: 1px solid transparent;
    letter-spacing: .01428571em;
    font-family: Roboto;
    font-size: .8rem;
    font-weight: 400;
    line-height: 1.25rem;
    padding: 5px 10px 5px 17px;
}
[data-tooltip=true].moreMenu {
    padding: 7px 0;
}


.modal-container[_ngcontent-hlx-c11] .modal[_ngcontent-hlx-c11] {
    position: absolute;
    transform: translate(-50%,-50%);
    left: 50%;
    top: 50%;
    transition: all .4s;
    max-width: 600px;
    width: 100%;
}
.modal-container[_ngcontent-hlx-c11] {
    position: fixed;
    display: none;
    z-index: 101;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: #202124d9;
    overflow: hidden;
}

[data-tooltip=true].labelMenu .label-list-container {
    padding: 6px 0;
}
[data-tooltip=true].colorMenu .second-row div.noimage {
    border-color: #5f6368;
    background-image: url()!important;
    background-repeat: no-repeat;
    background-position: center;
}

.placeholder[_ngcontent-hlx-c10] .picture[_ngcontent-hlx-c10] {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/picture.svg);
    right: 13px;
}
[data-tooltip=true].labelMenu {
    width: 225px;
    padding-top: 11px;
    background-color: #2d2e30;
}

[data-tooltip=true] {
    display: none;
    background-color: #202124;
    box-shadow: 0 1px 2px #0009, 0 2px 6px 2px #0000004d;
    border-radius: 4px;
    z-index: 999;
}
[data-tooltip=true].colorMenu .second-row div {
    width: 40px;
    height: 40px;
    margin: 2px;
    border: 2px solid transparent;
    border-radius: 50%;
    text-align: center;
    background-repeat: no-repeat;
    background-position: center;
}
.main-container[_ngcontent-hlx-c11] .pb-80[_ngcontent-hlx-c11] {
    padding-bottom: 80px;
}
.main-container[_ngcontent-hlx-c11] [_title][_ngcontent-hlx-c11] {
    color: #9aa0a6;
    letter-spacing: .07272727em;
    font-family: Roboto,Arial,sans-serif;
    font-size: .6875rem;
    font-weight: 500;
    line-height: 1rem;
    text-transform: uppercase;
    margin: 8px auto;
    transition: all .7s;
}
p {
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
}
section {
    display: block;
}
[data-tooltip=true].moreMenu div 
{
    border: 1px solid transparent;
    letter-spacing: .01428571em;
    font-family: Roboto;
    font-size: .8rem;
    font-weight: 400;
    line-height: 1.25rem;
    padding: 5px 10px 5px 17px;
}
.padding[_ngcontent-hlx-c12] {
    padding: 0 10px;
}

.w-100 {
    width: 100%!important;
}
.d-flex {
    display: flex!important;
}
.main-section[_ngcontent-hlx-c12] {
    padding-top: 8px;
}
.main-sidebar[_ngcontent-hlx-c8] .item.active[_ngcontent-hlx-c8] {
    background-color: #41331c;
}
*, *:before, *:after {
    box-sizing: border-box;
}
body {
    background-color: #202124;
    color: #fff;
    margin: 100px;
}
user agent stylesheet
section {
    display: block;
}
.note-main[_ngcontent-hlx-c10] .note-container[_ngcontent-hlx-c10] {
    background-position-x: right;
    background-position-y: bottom;
    background-size: cover;
}
.placeholder[_ngcontent-hlx-c10] .picture[_ngcontent-hlx-c10], .placeholder[_ngcontent-hlx-c10] .paint[_ngcontent-hlx-c10], .placeholder[_ngcontent-hlx-c10] .check[_ngcontent-hlx-c10] {
    height: 46px;
    position: absolute;
    top: 1px;
    width: 46px;
    background-repeat: no-repeat;
    background-position: center;
    opacity: .54;
}
.note-main[_ngcontent-hlx-c10] .note-container[_ngcontent-hlx-c10] .note-title.ph[_ngcontent-hlx-c10] {
    color: #fff9;
    position: absolute;
    width: 100%;
    pointer-events: none;
    padding-left: 11px;
}
.close-btn[_ngcontent-hlx-c10] {
    margin-right: 15px;
    color: #dadce0;
    letter-spacing: .01785714em;
    font-family: Google Sans;
    font-size: .875rem;
    font-weight: 500;
    line-height: 1.25rem;
    height: 36px;
    padding: 8px 24px;
    border-radius: 4px;
    cursor: pointer;
}
.note-main[_ngcontent-hlx-c10] {
    border: 1px solid #5f6368;
    border-radius: 8px;
    background-color: #202124;
}
.icons-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    margin: 4px 0;
    position: relative;
    justify-content: space-between;
}
.icons-container .icons .color {
    background-image: url(https://google-keep-clone-lovat.vercel.app/assets/images/svg/bg.svg);
}
.icons-container .icons {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}
.pin-icon {
    opacity: .54;
    height: 32px;
    width: 32px;
    right: 14px;
    top: 8px;
    position: absolute;

    background-position: center;
    background-repeat: no-repeat;
}
.item:hover
{
    background-color: #ffbb00;
}
icon:hover
{
    background-color: #ffbb00;
}
.labels-container {
    padding-left: 11px;
    padding-bottom: 5.5px;
}
.note-main[_ngcontent-hlx-c10] .note-container[_ngcontent-hlx-c10] .note-title[_ngcontent-hlx-c10] {
    padding: 10px 15px;
    letter-spacing: .00625em;
    font-family: Google Sans;
    font-size: 1rem;
    font-weight: 500;
    line-height: 1.5rem;
    white-space: pre-wrap;
    word-wrap: break-word;
}
</style>

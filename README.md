### このページの説明
<br>

**ブロられにくいYUKIの制作中**
<br>
### /home  
<br>
でYUKIのホームです。
<br>

### コードの変更
<br>

**/github-yuki/** 

<br>

**これは自分のリポジトリ名に変更してください。**

<a herf="./home"><img src="https://lms.catchon.jp/student/images/button/surala_logo_login.png" alt="logo" algin="center"></a><br>

<html lang="ja" style="--vh: 8.72px;">
	<!--<head>
		<meta name="robots" content="noindex,nofollow,none,noarchive">
		<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
		<meta http-equiv="Content-Style-Type" content="text/css">
		<meta name="viewport" content="initial-scale=0.811">
		<title>クリック！自立学習応援プログラム すらら</title>
		<script type="text/javascript" src="https://lms.catchon.jp/javascript/userAgent.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/student/javascript/overlay_window.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/javascript/lecture.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/student/javascript/study.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/javascript/keyEventChecker.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/student/javascript/mondai_disp_overlay.js"></script>
		<link rel="stylesheet" href="https://lms.catchon.jp/css/student_base.css" type="text/css">
		<!-- <link rel="stylesheet" href="https://lms.catchon.jp/css/student_base_standard.css" type="text/css"> -->
		<!--<link rel="stylesheet" href="https://lms.catchon.jp/teacher/Apl/css/toast.css">
		<script type="text/javascript" src="https://lms.catchon.jp/javascript/jquery-1.7.2.min.js"></script>
		<script type="text/javascript" src="https://lms.catchon.jp/teacher/Apl/javascript/toast.js"></script>
    <!-- common css -->
    <!--<link rel="stylesheet" href="https://lms.catchon.jp/css/surala_standard/renewal/ress.min.css">
    <link rel="stylesheet" href="https://lms.catchon.jp/css/surala_standard/renewal/simplebar.css">
    <link rel="stylesheet" href="https://lms.catchon.jp/css/surala_standard/renewal/myfont.css">
    <link rel="stylesheet" href="https://lms.catchon.jp/css/surala_standard/renewal/compiled.css">
    <!-- /common css -->
    <!-- common js -->
    <!--<script type="text/javascript" src="https://lms.catchon.jp/javascript/surala_standard/renewal/vendor/simplebar.min.js"></script>
    <script type="text/javascript" src="https://lms.catchon.jp/javascript/surala_standard/renewal/vendor/micromodal.min.js"></script>
    <!-- /common js -->
    <!--<link rel="stylesheet" href="https://lms.catchon.jp/css/surala_standard/renewal/standard_renewal_top.css">
    <script type="text/javascript" src="https://lms.catchon.jp/javascript/student_lms.js"></script>
 
	</head>-->
	<body onload="ifr_load_src('study_top.php', ''); ifr_resize_standard(); return false;" onresize="ifr_resize_standard();  return false;"> 
 <noscript>This site attempts to protect users against <a href="https://www.owasp.org/index.php/Cross-Site_Request_Forgery_%28CSRF%29">
	Cross-Site Request Forgeries </a> attacks. In order to do so, you must have JavaScript enabled in your web browser otherwise this site will fail to work correctly for you.
	 See details of your web browser for how to enable JavaScript.</noscript>
		<div id="index_gamification"></div>
		<div id="headerArea">
			<iframe name="head" id="head_check" frameborder="0" marginwidth="0" marginheight="0" src="https://lms.catchon.jp/lms.php" tabindex="-1"></iframe>
      <div class="hamburger-menu-btn-wrap" id="hamburger-menu-btn">
        <button type="button" class="header-menu-item fn-menu-open" onclick="getReplyNotify();" data-target="hamburgerMenu">
	<!-- add uenishi 2023/05/25 生徒画面改修開発-SMALL-443 -->
          <span class="hamburger-icon">
            <span></span>
            <span></span>
            <span></span>
          </span>
          <span class="header-menu-txt">メニュー</span>
        </button>
      </div>
      <div class="hamburger-menu" id="hamburgerMenu">
        <div class="hamburger-menu-bg"></div>
        <div class="hamburger-menu-content fn-class-add">
          <div class="hamburger-menu-inner">
            <button type="button" class="hamburger-menu-btn fn-menu-close">
            <img src="https://lms.catchon.jp/student/images/standard_renewal/common/hamburger_btn.png" alt=""></button>
            <ul class="hamburger-menu-list">
              <li class="hamburger-menu-item menu-ttl">メニュー</li>
              <li>
                <a href="javascript:void(0)" onclick="window.parent.frames[0].click_footer_btn('handle_name'); return false;" class="fn-menu-close">
                  <div class="hamburger-menu-item">
                    <i class="icon-setting"></i>
                    <p class="hamburger-menu-item-txt">
                      <span class="item-txt"><ruby>
                          <rb>個人設定</rb>
                          <rt>こじんせってい</rt>
                        </ruby></span>
                    </p>
                  </div>
                </a>
              </li>
              <li>
                <a href="javascript:void(0)" onclick="window.parent.frames[0].click_lms_btn('question'); return false;" class="fn-menu-close">
                  <div class="hamburger-menu-item has-new-icon">
                    <i class="icon-question"></i>
                    <p id="top-btn-question" class="hamburger-menu-item-txt">
                      <span class="item-txt">
                        <ruby>
                          <rb>質問</rb>
                          <rt>しつもん</rt>
                        </ruby>と<ruby>
                          <rb>回答</rb>
                          <rt>かいとう</rt>
                        </ruby>
                      </span>
                    </p>
                  </div>
                </a>
              </li>
              <li>
                <a href="javascript:void(0)" onclick="window.parent.frames[0].click_lms_btn('messages'); return false;" class="fn-menu-close">
                  <div class="hamburger-menu-item has-new-icon">
                    <i class="icon-message"></i>
                    <p class="hamburger-menu-item-txt">
                      <span id="top-btn-msg" class="item-txt">メッセージ</span>
                    </p>
                  </div>
                </a>
              </li>
              
              
              
                <a href="javascript:void(0)" onclick="window.parent.frames[0].click_lms_btn('cheer'); return false;" class="fn-menu-close">
                  <div class="hamburger-menu-item">
                    <i class="icon-speaker"></i>
                    <p class="hamburger-menu-item-txt">
                      <span class="item-txt">みんなからの<ruby>
                          <rb>応援</rb>
                          <rt>おうえん</rt>
                        </ruby></span>
                      <span class="hamburger-new-icon"><img src="https://lms.catchon.jp/student/images/standard_renewal/common/txt_new.png" alt="NEW"></span>
                    </p>
                  </div>
                </a>
              </li>
            
            </ul>
            <div class="hamburger-btn-wrap">
              
              <button type="button" onclick="window.parent.frames[0].click_lms_btn('logout'); return false;" class="btn-basic has-icon btn-color-reverse fn-menu-close"> 

              <button type="button" onclick="window.parent.frames[0].click_lms_btn('logout'); return false;" class="btn-basic has-icon btn-color-reverse fn-menu-close">
                <span class="btn-basic-inner">
                  <i class="icon-logout"></i>
                  <span>すららを<ruby>
                      <rb>終了</rb>
                      <rt>しゅうりょう</rt>
                    </ruby>する</span>
                </span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
		<div id="contentsArea">
			<iframe name="main" id="main_check" frameborder="0" marginwidth="0" marginheight="0" src="https://lms.catchon.jp/student/main_iframe.php?p=study_top.php" style="height: 772px;"></iframe>
		</div>
    <script src="https://lms.catchon.jp/javascript/surala_standard/renewal/common.js"></script>
    <script>
 
    
        getReplyNotifyTop();
 
        setInterval(getReplyNotifyTop, 53000);
 
        function getReplyNotifyTop(){
 
          $.ajax({
            url: "https://lms.catchon.jp/student/get_student_notify_controller.php",
            type: "get",
            dataType: "json",
            success: function (e){
              $('#hamburger-menu-new-icon').remove();
              if (parseInt(e.unread_thread_check) == 1){
                $('#hamburger-menu-btn').append('<span id="hamburger-menu-new-icon" class="hamburger-new-icon"><img src="https://lms.catchon.jp/student/images/standard_renewal/common/txt_new.png" alt="NEW"></span>');
              }
            },
            error: function (e){
              console.log(e);
            }
          });
        }
 
 
        $(function() {
          $('.hamburger-menu-btn').on('click', function(){
            getReplyNotifyTop()
          })
        });
 
 
        async function getReplyNotify(){
 
          getQuestionNotify();
          getMessageNotify();
 
          function getQuestionNotify(){
            $.ajax({
              url: "https://lms.catchon.jp/student/get_student_notify_controller.php",
              type: "get",
              dataType: "json",
              success: function (e){
                $('#question-new-message-icon').remove();
                if (parseInt(e.unread_question_count) > 0){
                  $('#top-btn-question').append('<span id="question-new-message-icon" class="hamburger-new-icon"><img src="https://lms.catchon.jp/student/images/standard_renewal/common/txt_new.png" alt="NEW"></span>');
                }
              },
              error: function (e){
                console.log(e);
              }
            });
          }
        
 
          function getMessageNotify(){
            $.ajax({
              url: "https://lms.catchon.jp/student/get_student_notify_message.php",
              type: "get",
              dataType: "json",
              success: function (e){
                if (e.status){
                  $('#msg-new-icon').remove();
                  if (parseInt(e.total_unread_msg) > 0){
                    $('#top-btn-msg').append('<span id="msg-new-icon" class="hamburger-new-icon">
                    <img src="https://lms.catchon.jp/student/images/standard_renewal/common/txt_new.png" alt="NEW"></span>');
                  }
                }
              },
              error: function (e){
                console.log(e);
              }
            });
          }
        } 
      </script>-->
	<input type="hidden" id="csrfp_hidden_data_token" value="csrfp_token">
<input type="hidden" id="csrfp_hidden_data_urls" value="[]">
<!--<script type="text/javascript" src="https://lms.catchon.jp/javascript/csrfprotector.js"></script>-->
 
<div class="gamification-timeleft" style="display: none;"></div>
<div class="gamification-timeleft" style="display: none;"></div></body>
</html>
<br>
©︎pokemogukunn

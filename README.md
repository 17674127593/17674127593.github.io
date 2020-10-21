<html>

<head>
  <meta charset="UTF-8" />
  <link rel="shortcut icon" href="http://cody1991.github.io/favicon.ico" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
  <title>codytang 个人简历</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=0">
  <link rel="stylesheet" type="text/css" href="./css/bootstrap.css">
  <link rel="stylesheet" type="text/css" href="./css/style.css">
  <link rel="stylesheet" href="./css/font-awesome.min.css">
</head>

<body>
  <div class="wrapper" id="wrapper">
    <header>
     
        <div class="bannerText container">
          <h1>我叫何庆佳</h1>
          <p>就读于湖南工商大学北津学院</p>
          <a href="#aboutme" class="mbnt">关于我</a>
        </div>
      </div>
      <div class="menu">
        <div class="navbar-wrapper">
          <div class="container">
            <div class="navwrapper">
              <div class="navbar navbar-inverse navbar-static-top">
                <div class="container">
                  <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                      <span class="icon-bar"></span>
                      <span class="icon-bar"></span>
                      <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="#">导航</a>
                  </div>
                  <div class="navbar-collapse collapse">
                    <ul class="nav navbar-nav nav-justified">
                      <li class="first menuItem homeLink active">
                        <a href="#wrapper">首页</a>
                      </li>
                      <li class="menuItem">
                        <a href="#aboutme">关于我</a>
                      </li>
                      <li class="menuItem">
                        <a href="#contact">联系我</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>
    <section class="aboutme" id="aboutme">
      <div class="container">
        <div class="row">
          <div class=" col-xs-12 col-sm-12 col-md-12 col-lg-12 aboutCont">
            <div class="heading clearfix">
              <h2>关于我</h2>
            </div>
            <div id="description">
              <p>
                我是来自湖南工商大学北津学院信息与计算科学的应届毕业生。
              </p>
              <p>
                我的专业让我有坚实的计算机基础.
              </p>
              <p>爱读书，爱听歌，爱游泳，爱跑步，爱爬山。代码不是生活的全部。</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="technical" id="technical">
      <div class="container">
        <div class="heading">
        </div>
          <h2>联系我</h2>
        </div>
      </div>
    </section>
    <section class="contactDetails">
      <div class="container">
        <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12">
          <h4>联系方式</h4>
          <p> <i class="icon icon-envelope"></i><a>2538320826@qq.com</a></p>
          <p> <i class="icon icon-link"></i><a href="http://cody1991.github.io/index.html">http://cody1991.github.io/</a>
          </p>
        </div>
      </div>
    </section>
    <section class="footer" id="footer">
      <div class="container">
        <ul>
          <li><a href="https://github.com/cody1991"><i class="icon icon-github icon-2x"></i></a>
          </li>
        </ul>
        <span class="totop"><i class="icon icon-chevron-up"></i>
                </span>
      </div>
    </section>
  </div>
  <script src="./js/jquery-2.1.4.min.js"></script>
  <script src="./js/bootstrap.js"></script>
  <script src="./js/jquery.waterfall.js"></script>
  <script src="./js/stickUp.js"></script>
  <script type="text/javascript">
  jQuery(function($) {
    $(document).ready(function() {
      //enabling stickUp on the '.navbar-wrapper' class

      $('.navbar-wrapper').stickUp({
        parts: {
          0: 'wrapper',
          1: 'aboutme',
          2: 'technical',
          3: 'exprience',
          4: 'reffernces',
          5: 'contact'
        },
        itemClass: 'menuItem',
        itemHover: 'active',
        topMargin: 'auto'
      });
    });
  });

  </script>
  <script src="./js/jquery.superslides.js"></script>
  <script src="./js/jquery.easing.min.js"></script>
  <script src="./js/custom.js"></script>
  <script src="js/jquery.easypiechart.js"></script>
</body>

</html>

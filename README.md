@{
    ViewBag.Title = "Home Page";
}

<html lang="en">
<head>
    <title></title>
    <link rel="shortcut icon" href="/files/atts/0I075385001830884494/layout/images/favicon.ico" />

    <link href="/css/content.css" rel="stylesheet" type="text/css" />
    <link href="/css/editable_content.css" rel="stylesheet" type="text/css" />

    <script src="/css/jquery.colorbox.js"></script>
    <script src="/css/jquery.datepicker.min.js"></script>

    <link href="~/Content/bootstrap.css" rel="stylesheet">
    <link href="~/Content/blog.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:700,900" rel="stylesheet">

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script>window.jQuery || document.write('<script src="/js src/jquery-3.3.1.slim.min.js"><\/script>')</script>
    <script src="/js src/bootstrap.bundle.js"></script>

    <link rel="stylesheet" href="//apps.bdimg.com/libs/jqueryui/1.10.4/css/jquery-ui.min.css">
    <script src="//apps.bdimg.com/libs/jquery/1.10.2/jquery.min.js"></script>
    <script src="//apps.bdimg.com/libs/jqueryui/1.10.4/jquery-ui.min.js"></script>

    <style>
        div.question_box.decide div.item div.title {
            cursor: pointer;
        }

        img {
            /*width: auto;*/
            height: auto;
            max-width: 100%;
            max-height: 100%;
        }

        .select input {
            display: none;
        }

            .select input + label {
                display: inline-block;
                border: 1px solid #000;
                cursor: pointer;
                border-radius: 4px;
                padding: 2px 8px;
            }

            .select input:checked + label {
                background-color: #FFFF00;
            }
    </style>
</head>

<body>
    <div class="bd-example">
        <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="~/img/sdm001.png" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="~/img/sdm002.png" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="~/img/sdm003.png" class="d-block w-100" alt="...">
                </div>
            </div>
            <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </div>

    <main role="main" class="container">
        <div class="row">
            <div class="col-md-8 blog-main">
                <div class="blog-post">
                    <h2 class="blog-post-title">醫病共享決策（SDM）緣起</h2>
                    <p class="blog-post-meta">
                        December 20, 2019
                    </p>
                    <hr>

                    <p>
                        「共享決策」（Shared Decision Making，SDM） 這個名詞最早是1982年美國以病人為中心照護的共同福祉計畫上，為促進醫病相互尊重與溝通而提出。在1997年由Charles提出操作型定義，至少要有醫師和病人雙方共同參與，醫師提出各種不同處置之實證資料，病人則提出個人的喜好與價值觀，彼此交換資訊討論，共同達成最佳可行之治療選項。
                    </p>
                    <p>
                        共享決策是以病人為中心的臨床醫療執行過程，兼具知識、溝通和尊重此三元素，目的是讓醫療人員和病人在進行醫療決策前，能夠共同享有現有的實證醫療結果，結合病人自身的偏好跟價值，提供病人所有可考量的選擇，並由臨床人員和病人共同參與醫療照護，達成醫療決策共識並支持病人做出符合其偏好的醫療決策。
                    </p>
                    <p>
                        為達到資源共享，因此建置SDM平台，此平台亦是決策輔助工具交流的平台，不但可以提供給有需要的醫療機構使用，亦可減少資源浪費。
                    </p>
                    <hr>

                    <h2>醫病共享決策輔助工具介紹</h2>
                    <p>
                        醫病共享輔助工具是專門為病人所設計的工具，協助病人了解疾病、臨床進程、治療選擇的意義，及提出自己在意的考量及期待，利用圖形化的說明及互動式的工具，以最新的實證醫學證據用病人能夠理解的方式做說明，為醫師及病人做出共同的醫療決策，藉以提升醫病溝通的效率。
                    </p>
                    <hr>
                    <h3>醫病共享決策輔助工具目的</h3>
                    <ul>
                        <li>減輕醫療人員準備溝通資訊的負擔</li>
                        <li>幫助病人表達重要的好惡與價值觀</li>
                        <li>確認病人已瞭解做決定前應該具備的疾病或治療知識</li>
                        <li>降低病人決策前的焦慮</li>
                        <li>提升病人參與醫療決策</li>
                        <li>提升病人對醫療服務滿意度</li>
                        <li>增加病人對於醫療的順從度</li>
                        <li>提升醫療品質</li>
                        <li>建立更好醫病關係</li>
                    </ul>
                    <hr />
                    <h3>目前可執行的主題</h3>
                    @*<h4 style="color:forestgreen;font-weight:bold">子宮頸癌：</h4>*@
                    <nav class="blog-pagination">
                        <a class="btn btn-outline-primary" href="~/img/pdf01.pdf">子宮頸癌</a>
                        <a class="btn btn-outline-primary" href="~/img/pdf02.pdf">氣管造口術</a>
                        <a class="btn btn-outline-primary" href="~/img/pdf03.pdf">慢性腎臟疾病</a>
                    </nav>
                </div>
                <hr />
                <iframe style="width:100%; height:480px;" src="https://www.youtube.com/embed/sSFg1sSMx6w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                @*<nav class="blog-pagination">
                        <a class="btn btn-outline-primary" href="#">回到最頂</a>
                    </nav>*@
            </div>

            <aside class="col-md-4 blog-sidebar">
                <div class="p-3 mb-3 bg-light rounded">
                    <h4 class="font-italic">Shared Decision Making</h4>
                    <p class="mb-0">
                        Shared Decision Making is a process in which both the patient and physician contribute to the medical decision-making process. Health care providers explain treatments and alternatives to patients and help them choose the treatment option that best aligns with their preferences as well as their unique cultural and personal beliefs.
                    </p>
                </div>

                <div class="p-3">
                    <h4 class="font-weight-bold">相關網站</h4>
                    <ol class="list-unstyled">
                        <li>
                            <a href="https://www.jct.org.tw/mp-1.html">財團法人醫院評鑑暨醫療品質策進會</a>
                        </li>
                        <li>
                            <a href="https://sdm.patientsafety.mohw.gov.tw/">衛生福利部–醫病共享決策平台</a>
                        </li>
                        <li>
                            <a href="https://www.nhi.gov.tw/">衛生福利部中央健康保險署</a>
                        </li>
                        <li>
                            <a href="https://www.skh.org.tw/skh/index.html">新光吳火獅紀念醫院</a>
                        </li>
                        <li>
                            <a href="http://www.patientsafety.mohw.gov.tw/">台灣病人安全資訊網</a>
                        </li>
                        <li>
                            <a href="https://www.mohw.gov.tw/mp-1.html">衛生福利部</a>
                        </li>
                        @*<li>
                            <a href="~/Logins/Login">登入</a>
                        </li>
                        <li>
                            <a href="~/Kidplazas/Index">子宮頸癌</a>
                        </li>
                        <li>
                            <a href="~/AircutLists/Index">氣管造口術</a>
                        </li>
                        <li>
                            <a href="~/Kidneys/Index">慢性腎臟疾病</a>
                        </li>*@
                    </ol>
                </div>
            </aside><!-- /.blog-sidebar -->
        </div><!-- /.row -->
    </main><!-- /.container -->
    <footer class="blog-footer">
        <p>
            <a href="#">Back to top</a>
        </p>
    </footer>
</body>
</html>

<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
          integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"
            integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q"
            crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"
            integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl"
            crossorigin="anonymous"></script>

    <title>Hello:) 휘둥그레</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap" rel="stylesheet">

    <style>
        * {
            font-family: 'Nanum Pen Script', cursive;
            font-size: large

        }
        .wrap {
            width: 900px;
            margin: auto;
        }
        .bluetag {
            color: red;
            text-align: center;
        }
        .card-title {
            font-weight: bold;
        }

        .posting-box {
            width: 500px;
            margin: auto;
            border-style: solid;
            border-color: black;
            border-radius: 10px;
            padding: 30px;
            margin: 0px auto 20px auto


        }
    </style>

    <script>
        let count = 1;
        function hey() {
            if (count % 2 == 0){
                alert('짝수입니다')
            } else {
                alert('홀수입니다!')
            }
            count += 1;
           


        }
    </script>

</head>

<body>
    <div class="wrap">
        <div class="jumbotron">
        <h1 class="display-4">Hello:) 휘둥그레</h1>
        <p class="lead">좋은 재료로 정성스레 만든 뒤, 따끈따끈 하게 보내드립니다.</p>
        <hr class="my-4">
        <p>주문 당일 베이킹, 다음날 배송.</p>
        <p class="lead">
            <a onclick="hey()" class="btn btn-primary btn-lg" href="#" role="button">다른 종류의 디저트 보기</a>
        </p>
    </div>

    <div class="posting-box">
        <div class="form-group">
          <label for="exampleInputEmail1">이름</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
        <div class="form-group">
            <label for="exampleFormControlTextarea1">간단 코멘트</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
          </div>

        <button type="submit" class="btn btn-primary">Submit</button>

    </div>


        <div class="card-columns">
        <div class="card">
            <img class="card-img-top" src="https://i.pinimg.com/736x/83/cf/97/83cf97aacc9a803bad044b3eed2b4684.jpg" alt="Card image cap">
            <div class="card-body">
                <a href="https://m.blog.naver.com/alfoalalfofo/220494571157" class="card-title">휘낭시에 클래식</a>
                <p class="card-text">기본 휘낭시에입니다.</p>
                <p class="bluetag">*BEST DESERT*</p>
            </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://image.jtbcplus.kr/data/contents/jam_photo/202105/20/f84dbf3a-a3b7-4197-b243-f0fdcccbd77a.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">화이트 초코 휘낭시에</h5>
                <p class="card-text">화이트 초코를 바른 휘낭시에 입니다.</p>
            </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://ssproxy.ucloudbiz.olleh.com/v1/AUTH_e59809eb-bdc9-44d7-9d8f-2e7f0e47ba91/uploads/ds_15718_1611107600nQ0Eopl.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">너츠 휘낭시에</h5>
                <p class="card-text">견과류와 함께 구워낸 휘낭시에입니다.</p>
            </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://th.bing.com/th/id/OIP.vzl5h3Q3ewbZ4NJ75ku6fgHaE8?pid=ImgDet&rs=1" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">다크초코 휘낭시에</h5>
                <p class="card-text">다크 초코를 바른 휘낭시에 입니다.</p>
            </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://recipe1.ezmember.co.kr/cache/recipe/2015/12/21/a8703615b9c9f11bfbf1c0a4ae2842a71.jpg" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">딸기잼 휘낭시에</h5>
                <p class="card-text">딸기잼이 들어간 휘낭시에 입니다.</p>
                <p class="bluetag">*BEST DESERT*</p>
            </div>
        </div>
        <div class="card">
            <img class="card-img-top" src="https://t1.daumcdn.net/cfile/tistory/99BDB8435B52D3B214" alt="Card image cap">
            <div class="card-body">
                <h5 class="card-title">녹차 휘낭시에</h5>
                <p class="card-text">녹차 휘낭시에 입니다.</p>
            </div>
        </div>
    </div>

    </div>
</body>

</html>

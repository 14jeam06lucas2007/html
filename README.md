<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="minimal-ui, width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

    <title>Ouro Moderno - Versão 5.17.4</title>
    <link rel='shortcut icon' type='image/x-icon' href='favicon.ico' />
    <link rel='icon' href='favicon.ico' />
    <link href="_css/reset.css?v=5.17.4" type="text/css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="_assets/normalize.css">
        <link rel="stylesheet" href="_assets/bootstrap/bootstrap.min.css">
    <link rel="stylesheet" href="_assets/font-awesome/css/font-awesome.min.css">

    
        <script src="_inc/js/jquery-3.2.1.min.js"></script>
        <script src="_assets/bootstrap/popper.min.js"></script>
        <script src="_assets/bootstrap/bootstrap.min.js"></script>
        <link href="_css/login.css?v=5.17.4" type="text/css" rel="stylesheet" />
        <link href="_css/login.custom.css?v=5.17.4" type="text/css" rel="stylesheet" />

    
    <script src="_assets/core.js"></script>
    <script src="_assets/sweetalert2.all.min.js"></script>
    <script src="_inc/js/alertas.js"></script>
    <script src="_inc/js/main.js"></script>
    <script type="text/javascript" src="_inc/js/funcoes.js?v=5.17.4"></script>

    <link href="_css/temas/light.css?v=5.17.4" type="text/css" rel="stylesheet" /></head>

<body id="pag-login" class="tema-light   ">
    <link href="_css/loader-wrapper.css" type="text/css" rel="stylesheet">
<script type="text/javascript">
    $(document).ready(function() {
        $('body').addClass('loaded');
    });
</script>
<div id="loader-wrapper">
    <div id="loader"></div>
    <div class="loader-section section-left"></div>
    <div class="loader-section section-right"></div>
</div><section class="login-block">
  <a href="javascript:void(0);" onclick="fechar()" id="fechar">Fechar</a>

      <div id="idioma_login" class="dropdown">
      <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <i class="fa fa-language" aria-hidden="true"></i>
      </button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <button type="button" class="dropdown-item active" onclick="set_language('pt')"><img src="_img/icones/idiomas/pt.png"> Português</button>
        <button type="button" class="dropdown-item " onclick="set_language('es')"><img src="_img/icones/idiomas/es.png"> Espanhol</button>

      </div>
    </div>
  
    <div class="container" >
    <div class="row justify-content-center">
      <div class="col-md-4 login-sec row m-0" id="login-sec">
        <div class="my-auto">

          <img src="_img/_liquido/custom/logoLogin.png" alt="Logo" class="w-100 img-fluid" />


                      <style>
              #login-sec .form-group {
                position: relative;
                margin-bottom: 1.5rem;
              }

              #login-sec .form-control {
                padding: 0 !important;
                padding-bottom: 10px;
                height: auto !important;
                border-radius: 0 !important;
                border: 0;
                border-bottom: solid 1px #000;
              }

              #login-sec .form-control:hover,
              #login-sec .form-control:focus {
                box-shadow: none;
              }

              #login-sec .form-control-placeholder {
                position: absolute;
                top: 0;
                left: 40px;
                padding: 0;
                transition: all 200ms;
                opacity: 0.5;
              }

              #login-sec .form-control:focus+.form-control-placeholder,
              #login-sec .form-control:valid+.form-control-placeholder {
                font-size: 75%;
                transform: translate3d(0, -100%, 0);
                opacity: 1;
              }
            </style>
          
          <h2 class="text-center">Digite seu usuário e senha</h2>
                      <form class="login-form mt-4" action="logar.php?acao=logar" method="post" autocomplete="off">
              <div class="form-group">
                <div class="loading"></div>
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-user" aria-hidden="true"></i></span>
                  </div>
                  <input type="text" name="aluno" id="aluno" class="campo form-control" autocomplete="off" required>
                  <label class="form-control-placeholder" for="aluno">Usuário</label>
                </div>
              </div>
              <div class="form-group">
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-key" aria-hidden="true"></i></span>
                  </div>
                  <input type="password" name="senha" id="senha" class="campo form-control" autocomplete="new-password" required>
                  <label class="form-control-placeholder" for="senha">Senha</label>
                </div>
              </div>
              <div class="form-group text-center">
                <button type="submit" class="btn btn-primary  btn-login rounded-pill mt-1 px-5">Acessar <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></button>
              </div>
            </form>
                    <div id="alert-navegador"></div>
        </div>
      </div>

      
        <div class="col-md-8 banner-sec">

          <div id="carouselLogin" class="carousel slide" data-ride="carousel" data-interval="10000">
            <!--carousel-->
            <ol class="carousel-indicators">
                              <li data-target="#carouselLogin" data-slide-to="0" class="active"></li>

                                                              <li data-target="#carouselLogin"  data-slide-to="1"></li>
                  <li data-target="#carouselLogin" data-slide-to="2"></li>
                  <li data-target="#carouselLogin" data-slide-to="3"></li>
                  <li data-target="#carouselLogin" data-slide-to="4"></li>
                  <li data-target="#carouselLogin" data-slide-to="5"></li>
                  <li data-target="#carouselLogin" data-slide-to="6"></li>
                            </ol>
            <div class="carousel-inner" role="listbox">
                              
                  <div class="carousel-item active">

                    <div class="GridAnimadoBagual">
                      <img class="img-fluid" src="_img/login_slide/1.jpeg" alt="">
                      <div id="GridAnimadoBagual">
                        <div class="coluna" id="column-1">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/85-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/2-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/138-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/155-thumb.png')"></div>
                          
                        </div>
                        <div class="coluna" id="column-2">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/561-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/88-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/360-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/65-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-3">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/252-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/47-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/127-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/4-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-4">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/40-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/75-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/266-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/159-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-5">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/46-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/106-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/639-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/628-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-6">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/139-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/73-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/61-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/271-thumb.png')"></div>
                                                  </div>
                      </div>
                    </div>
                  </div>

                              
              
                                <div class="carousel-item ">
                    <img class="img-fluid" src="_img/login_slide/2.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/3.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/4.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/5.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/6.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/7.jpg?v=1" alt="">
                  </div>
                
            </div>
          </div>
        </div>
          </div>

</section>
<script type="text/javascript">
  $('form').submit(function(event) {
    $('body').removeClass('loaded');
  });
</script>
  <link rel="stylesheet" href="_assets/gridanimadobagual/jquery.gridanimadobagual.css">
  <script src="_assets/gridanimadobagual/jquery.gridanimadobagual.js"></script>

  <script type="text/javascript">
    // popula a variavel 'imagens_1' com as thumb dos cursos  
    var thumbs = [
      "_img/icones/cursos/85-thumb.png","_img/icones/cursos/2-thumb.png","_img/icones/cursos/138-thumb.png","_img/icones/cursos/155-thumb.png","_img/icones/cursos/561-thumb.png","_img/icones/cursos/88-thumb.png","_img/icones/cursos/360-thumb.png","_img/icones/cursos/65-thumb.png","_img/icones/cursos/252-thumb.png","_img/icones/cursos/47-thumb.png","_img/icones/cursos/127-thumb.png","_img/icones/cursos/4-thumb.png","_img/icones/cursos/40-thumb.png","_img/icones/cursos/75-thumb.png","_img/icones/cursos/266-thumb.png","_img/icones/cursos/159-thumb.png","_img/icones/cursos/46-thumb.png","_img/icones/cursos/106-thumb.png","_img/icones/cursos/639-thumb.png","_img/icones/cursos/628-thumb.png","_img/icones/cursos/139-thumb.png","_img/icones/cursos/73-thumb.png","_img/icones/cursos/61-thumb.png","_img/icones/cursos/271-thumb.png","_img/icones/cursos/153-thumb.png","_img/icones/cursos/21-thumb.png","_img/icones/cursos/627-thumb.png","_img/icones/cursos/218-thumb.png","_img/icones/cursos/195-thumb.png","_img/icones/cursos/63-thumb.png","_img/icones/cursos/92-thumb.png","_img/icones/cursos/167-thumb.png","_img/icones/cursos/11-thumb.png","_img/icones/cursos/67-thumb.png","_img/icones/cursos/68-thumb.png","_img/icones/cursos/237-thumb.png","_img/icones/cursos/32-thumb.png","_img/icones/cursos/659-thumb.png","_img/icones/cursos/281-thumb.png","_img/icones/cursos/13-thumb.png","_img/icones/cursos/200-thumb.png","_img/icones/cursos/160-thumb.png","_img/icones/cursos/253-thumb.png","_img/icones/cursos/3-thumb.png","_img/icones/cursos/197-thumb.png","_img/icones/cursos/207-thumb.png","_img/icones/cursos/81-thumb.png","_img/icones/cursos/58-thumb.png","_img/icones/cursos/236-thumb.png","_img/icones/cursos/222-thumb.png","_img/icones/cursos/53-thumb.png","_img/icones/cursos/220-thumb.png","_img/icones/cursos/255-thumb.png","_img/icones/cursos/131-thumb.png","_img/icones/cursos/66-thumb.png","_img/icones/cursos/126-thumb.png","_img/icones/cursos/276-thumb.png","_img/icones/cursos/123-thumb.png","_img/icones/cursos/513-thumb.png","_img/icones/cursos/169-thumb.png","_img/icones/cursos/149-thumb.png","_img/icones/cursos/355-thumb.png","_img/icones/cursos/1-thumb.png","_img/icones/cursos/38-thumb.png","_img/icones/cursos/238-thumb.png","_img/icones/cursos/198-thumb.png","_img/icones/cursos/734-thumb.png","_img/icones/cursos/51-thumb.png","_img/icones/cursos/64-thumb.png","_img/icones/cursos/104-thumb.png","_img/icones/cursos/135-thumb.png","_img/icones/cursos/107-thumb.png","_img/icones/cursos/94-thumb.png","_img/icones/cursos/396-thumb.png","_img/icones/cursos/192-thumb.png","_img/icones/cursos/133-thumb.png","_img/icones/cursos/183-thumb.png","_img/icones/cursos/163-thumb.png","_img/icones/cursos/235-thumb.png","_img/icones/cursos/263-thumb.png","_img/icones/cursos/317-thumb.png","_img/icones/cursos/162-thumb.png","_img/icones/cursos/568-thumb.png","_img/icones/cursos/93-thumb.png","_img/icones/cursos/242-thumb.png","_img/icones/cursos/72-thumb.png","_img/icones/cursos/240-thumb.png","_img/icones/cursos/6-thumb.png","_img/icones/cursos/69-thumb.png","_img/icones/cursos/105-thumb.png","_img/icones/cursos/87-thumb.png","_img/icones/cursos/316-thumb.png","_img/icones/cursos/124-thumb.png","_img/icones/cursos/78-thumb.png","_img/icones/cursos/102-thumb.png","_img/icones/cursos/70-thumb.png","_img/icones/cursos/52-thumb.png","_img/icones/cursos/156-thumb.png","_img/icones/cursos/90-thumb.png","_img/icones/cursos/41-thumb.png","_img/icones/cursos/77-thumb.png","_img/icones/cursos/23-thumb.png","_img/icones/cursos/15-thumb.png","_img/icones/cursos/334-thumb.png","_img/icones/cursos/541-thumb.png","_img/icones/cursos/270-thumb.png","_img/icones/cursos/560-thumb.png","_img/icones/cursos/59-thumb.png","_img/icones/cursos/770-thumb.png","_img/icones/cursos/74-thumb.png","_img/icones/cursos/146-thumb.png","_img/icones/cursos/80-thumb.png","_img/icones/cursos/91-thumb.png","_img/icones/cursos/62-thumb.png","_img/icones/cursos/43-thumb.png","_img/icones/cursos/98-thumb.png","_img/icones/cursos/426-thumb.png","_img/icones/cursos/176-thumb.png","_img/icones/cursos/100-thumb.png","_img/icones/cursos/202-thumb.png","_img/icones/cursos/19-thumb.png","_img/icones/cursos/619-thumb.png","_img/icones/cursos/265-thumb.png","_img/icones/cursos/28-thumb.png","_img/icones/cursos/57-thumb.png","_img/icones/cursos/144-thumb.png","_img/icones/cursos/128-thumb.png","_img/icones/cursos/17-thumb.png","_img/icones/cursos/99-thumb.png","_img/icones/cursos/594-thumb.png","_img/icones/cursos/35-thumb.png","_img/icones/cursos/193-thumb.png","_img/icones/cursos/25-thumb.png","_img/icones/cursos/164-thumb.png","_img/icones/cursos/473-thumb.png","_img/icones/cursos/201-thumb.png","_img/icones/cursos/441-thumb.png","_img/icones/cursos/775-thumb.png","_img/icones/cursos/130-thumb.png","_img/icones/cursos/251-thumb.png","_img/icones/cursos/33-thumb.png","_img/icones/cursos/44-thumb.png","_img/icones/cursos/18-thumb.png","_img/icones/cursos/129-thumb.png","_img/icones/cursos/562-thumb.png","_img/icones/cursos/50-thumb.png","_img/icones/cursos/216-thumb.png","_img/icones/cursos/705-thumb.png","_img/icones/cursos/82-thumb.png","_img/icones/cursos/284-thumb.png","_img/icones/cursos/103-thumb.png","_img/icones/cursos/60-thumb.png","_img/icones/cursos/34-thumb.png","_img/icones/cursos/5-thumb.png","_img/icones/cursos/49-thumb.png","_img/icones/cursos/10-thumb.png","_img/icones/cursos/590-thumb.png","_img/icones/cursos/268-thumb.png","_img/icones/cursos/79-thumb.png","_img/icones/cursos/148-thumb.png","_img/icones/cursos/12-thumb.png","_img/icones/cursos/243-thumb.png","_img/icones/cursos/20-thumb.png","_img/icones/cursos/203-thumb.png","_img/icones/cursos/26-thumb.png","_img/icones/cursos/182-thumb.png","_img/icones/cursos/31-thumb.png","_img/icones/cursos/16-thumb.png","_img/icones/cursos/24-thumb.png","_img/icones/cursos/280-thumb.png","_img/icones/cursos/83-thumb.png","_img/icones/cursos/101-thumb.png","_img/icones/cursos/221-thumb.png","_img/icones/cursos/161-thumb.png","_img/icones/cursos/7-thumb.png","_img/icones/cursos/234-thumb.png","_img/icones/cursos/37-thumb.png","_img/icones/cursos/14-thumb.png","_img/icones/cursos/199-thumb.png","_img/icones/cursos/45-thumb.png","_img/icones/cursos/771-thumb.png","_img/icones/cursos/8-thumb.png","_img/icones/cursos/217-thumb.png","_img/icones/cursos/239-thumb.png","_img/icones/cursos/134-thumb.png","_img/icones/cursos/56-thumb.png","_img/icones/cursos/84-thumb.png","_img/icones/cursos/710-thumb.png","_img/icones/cursos/754-thumb.png","_img/icones/cursos/214-thumb.png","_img/icones/cursos/599-thumb.png","_img/icones/cursos/154-thumb.png","_img/icones/cursos/89-thumb.png","_img/icones/cursos/307-thumb.png","_img/icones/cursos/30-thumb.png","_img/icones/cursos/264-thumb.png","_img/icones/cursos/278-thumb.png","_img/icones/cursos/29-thumb.png","_img/icones/cursos/54-thumb.png","_img/icones/cursos/71-thumb.png","_img/icones/cursos/55-thumb.png","_img/icones/cursos/36-thumb.png","_img/icones/cursos/76-thumb.png","_img/icones/cursos/196-thumb.png","_img/icones/cursos/168-thumb.png","_img/icones/cursos/42-thumb.png","_img/icones/cursos/27-thumb.png","_img/icones/cursos/48-thumb.png","_img/icones/cursos/254-thumb.png","_img/icones/cursos/39-thumb.png","_img/icones/cursos/136-thumb.png",    ];

    // passa um array com as thumbs e tempo entre animações      
    GridAnimadoBagual(thumbs, 1000);
  </script>
  <script type="text/javascript">
    localStorage.clear();
    let teste_de_navegador

    $(document).ready(function() {

      navigator.sayswho = (function() {
        var ua = navigator.userAgent,
          tem,
          M = ua.match(/(opera|chrome|safari|firefox|msie|trident(?=\/))\/?\s*(\d+)/i) || [];
        if (/trident/i.test(M[1])) {
          tem = /\brv[ :]+(\d+)/g.exec(ua) || [];
          return 'IE ' + (tem[1] || '');
        }
        if (M[1] === 'Chrome') {
          tem = ua.match(/\b(OPR|Edge)\/(\d+)/);
          if (tem != null) return tem.slice(1).join(' ').replace('OPR', 'Opera');
        }
        M = M[2] ? [M[1], M[2]] : [navigator.appName, navigator.appVersion, '-?'];
        if ((tem = ua.match(/version\/(\d+)/i)) != null) M.splice(1, 1, tem[1]);
        return M.join(' ');
      })();

      teste_de_navegador = navigator.sayswho.split(" ");

      if (teste_de_navegador[0] == 'Chrome') {
        if (check_chrome_ua()) {
          $("#fechar").html("Para fechar utilize as teclas ALT + F4");
        }
      }

      if (teste_de_navegador[0] == 'MSIE' && teste_de_navegador[1] < 10) {
        var html = '<div class="alert alert-warning" style="margin-top: 15px; line-height: 1.1;"><small><strong>Alerta!!</strong> Você está utilizando uma versão desatualizada do navegador, recomendamos que atualize o seu navegador para uma melhor experiência de nosso método de ensino. <a href="http://www.updateyourbrowser.net/pt" target="_blank">Clique aqui para atualizar</a></small></div>'
        $("#alert-navegador").html(html);
      } else {
        $("#alert-navegador").remove();
      }

      fetch('chkl.php');

    });
  </script>
    <div class="clearfix">
    </div>
            <script type="text/javascript">
            var adblock = true;
        </script>
        <script type="text/javascript" src="_inc/js/adframe.js"></script>
        <script type="text/javascript">
            if (adblock) {
                swal({
                    title: 'AdBlock Instalado',
                    html: 'AdBlock pode causar problemas na utilização do método. Favor desativar o AdBlock.',
                    type: 'error'
                })
            }
        </script>
        <div id="carregando" style="display: none;"></div>
</body>

</html><!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="minimal-ui, width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

    <title>Ouro Moderno - Versão 5.17.4</title>
    <link rel='shortcut icon' type='image/x-icon' href='favicon.ico' />
    <link rel='icon' href='favicon.ico' />
    <link href="_css/reset.css?v=5.17.4" type="text/css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="_assets/normalize.css">
        <link rel="stylesheet" href="_assets/bootstrap/bootstrap.min.css">
    <link rel="stylesheet" href="_assets/font-awesome/css/font-awesome.min.css">

    
        <script src="_inc/js/jquery-3.2.1.min.js"></script>
        <script src="_assets/bootstrap/popper.min.js"></script>
        <script src="_assets/bootstrap/bootstrap.min.js"></script>
        <link href="_css/login.css?v=5.17.4" type="text/css" rel="stylesheet" />
        <link href="_css/login.custom.css?v=5.17.4" type="text/css" rel="stylesheet" />

    
    <script src="_assets/core.js"></script>
    <script src="_assets/sweetalert2.all.min.js"></script>
    <script src="_inc/js/alertas.js"></script>
    <script src="_inc/js/main.js"></script>
    <script type="text/javascript" src="_inc/js/funcoes.js?v=5.17.4"></script>

    <link href="_css/temas/light.css?v=5.17.4" type="text/css" rel="stylesheet" /></head>

<body id="pag-login" class="tema-light   ">
    <link href="_css/loader-wrapper.css" type="text/css" rel="stylesheet">
<script type="text/javascript">
    $(document).ready(function() {
        $('body').addClass('loaded');
    });
</script>
<div id="loader-wrapper">
    <div id="loader"></div>
    <div class="loader-section section-left"></div>
    <div class="loader-section section-right"></div>
</div><section class="login-block">
  <a href="javascript:void(0);" onclick="fechar()" id="fechar">Fechar</a>

      <div id="idioma_login" class="dropdown">
      <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <i class="fa fa-language" aria-hidden="true"></i>
      </button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <button type="button" class="dropdown-item active" onclick="set_language('pt')"><img src="_img/icones/idiomas/pt.png"> Português</button>
        <button type="button" class="dropdown-item " onclick="set_language('es')"><img src="_img/icones/idiomas/es.png"> Espanhol</button>

      </div>
    </div>
  
    <div class="container" >
    <div class="row justify-content-center">
      <div class="col-md-4 login-sec row m-0" id="login-sec">
        <div class="my-auto">

          <img src="_img/_liquido/custom/logoLogin.png" alt="Logo" class="w-100 img-fluid" />


                      <style>
              #login-sec .form-group {
                position: relative;
                margin-bottom: 1.5rem;
              }

              #login-sec .form-control {
                padding: 0 !important;
                padding-bottom: 10px;
                height: auto !important;
                border-radius: 0 !important;
                border: 0;
                border-bottom: solid 1px #000;
              }

              #login-sec .form-control:hover,
              #login-sec .form-control:focus {
                box-shadow: none;
              }

              #login-sec .form-control-placeholder {
                position: absolute;
                top: 0;
                left: 40px;
                padding: 0;
                transition: all 200ms;
                opacity: 0.5;
              }

              #login-sec .form-control:focus+.form-control-placeholder,
              #login-sec .form-control:valid+.form-control-placeholder {
                font-size: 75%;
                transform: translate3d(0, -100%, 0);
                opacity: 1;
              }
            </style>
          
          <h2 class="text-center">Digite seu usuário e senha</h2>
                      <form class="login-form mt-4" action="logar.php?acao=logar" method="post" autocomplete="off">
              <div class="form-group">
                <div class="loading"></div>
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-user" aria-hidden="true"></i></span>
                  </div>
                  <input type="text" name="aluno" id="aluno" class="campo form-control" autocomplete="off" required>
                  <label class="form-control-placeholder" for="aluno">Usuário</label>
                </div>
              </div>
              <div class="form-group">
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-key" aria-hidden="true"></i></span>
                  </div>
                  <input type="password" name="senha" id="senha" class="campo form-control" autocomplete="new-password" required>
                  <label class="form-control-placeholder" for="senha">Senha</label>
                </div>
              </div>
              <div class="form-group text-center">
                <button type="submit" class="btn btn-primary  btn-login rounded-pill mt-1 px-5">Acessar <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></button>
              </div>
            </form>
                    <div id="alert-navegador"></div>
        </div>
      </div>

      
        <div class="col-md-8 banner-sec">

          <div id="carouselLogin" class="carousel slide" data-ride="carousel" data-interval="10000">
            <!--carousel-->
            <ol class="carousel-indicators">
                              <li data-target="#carouselLogin" data-slide-to="0" class="active"></li>

                                                              <li data-target="#carouselLogin"  data-slide-to="1"></li>
                  <li data-target="#carouselLogin" data-slide-to="2"></li>
                  <li data-target="#carouselLogin" data-slide-to="3"></li>
                  <li data-target="#carouselLogin" data-slide-to="4"></li>
                  <li data-target="#carouselLogin" data-slide-to="5"></li>
                  <li data-target="#carouselLogin" data-slide-to="6"></li>
                            </ol>
            <div class="carousel-inner" role="listbox">
                              
                  <div class="carousel-item active">

                    <div class="GridAnimadoBagual">
                      <img class="img-fluid" src="_img/login_slide/1.jpeg" alt="">
                      <div id="GridAnimadoBagual">
                        <div class="coluna" id="column-1">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/85-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/2-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/138-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/155-thumb.png')"></div>
                          
                        </div>
                        <div class="coluna" id="column-2">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/561-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/88-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/360-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/65-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-3">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/252-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/47-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/127-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/4-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-4">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/40-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/75-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/266-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/159-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-5">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/46-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/106-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/639-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/628-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-6">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/139-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/73-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/61-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/271-thumb.png')"></div>
                                                  </div>
                      </div>
                    </div>
                  </div>

                              
              
                                <div class="carousel-item ">
                    <img class="img-fluid" src="_img/login_slide/2.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/3.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/4.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/5.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/6.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/7.jpg?v=1" alt="">
                  </div>
                
            </div>
          </div>
        </div>
          </div>

</section>
<script type="text/javascript">
  $('form').submit(function(event) {
    $('body').removeClass('loaded');
  });
</script>
  <link rel="stylesheet" href="_assets/gridanimadobagual/jquery.gridanimadobagual.css">
  <script src="_assets/gridanimadobagual/jquery.gridanimadobagual.js"></script>

  <script type="text/javascript">
    // popula a variavel 'imagens_1' com as thumb dos cursos  
    var thumbs = [
      "_img/icones/cursos/85-thumb.png","_img/icones/cursos/2-thumb.png","_img/icones/cursos/138-thumb.png","_img/icones/cursos/155-thumb.png","_img/icones/cursos/561-thumb.png","_img/icones/cursos/88-thumb.png","_img/icones/cursos/360-thumb.png","_img/icones/cursos/65-thumb.png","_img/icones/cursos/252-thumb.png","_img/icones/cursos/47-thumb.png","_img/icones/cursos/127-thumb.png","_img/icones/cursos/4-thumb.png","_img/icones/cursos/40-thumb.png","_img/icones/cursos/75-thumb.png","_img/icones/cursos/266-thumb.png","_img/icones/cursos/159-thumb.png","_img/icones/cursos/46-thumb.png","_img/icones/cursos/106-thumb.png","_img/icones/cursos/639-thumb.png","_img/icones/cursos/628-thumb.png","_img/icones/cursos/139-thumb.png","_img/icones/cursos/73-thumb.png","_img/icones/cursos/61-thumb.png","_img/icones/cursos/271-thumb.png","_img/icones/cursos/153-thumb.png","_img/icones/cursos/21-thumb.png","_img/icones/cursos/627-thumb.png","_img/icones/cursos/218-thumb.png","_img/icones/cursos/195-thumb.png","_img/icones/cursos/63-thumb.png","_img/icones/cursos/92-thumb.png","_img/icones/cursos/167-thumb.png","_img/icones/cursos/11-thumb.png","_img/icones/cursos/67-thumb.png","_img/icones/cursos/68-thumb.png","_img/icones/cursos/237-thumb.png","_img/icones/cursos/32-thumb.png","_img/icones/cursos/659-thumb.png","_img/icones/cursos/281-thumb.png","_img/icones/cursos/13-thumb.png","_img/icones/cursos/200-thumb.png","_img/icones/cursos/160-thumb.png","_img/icones/cursos/253-thumb.png","_img/icones/cursos/3-thumb.png","_img/icones/cursos/197-thumb.png","_img/icones/cursos/207-thumb.png","_img/icones/cursos/81-thumb.png","_img/icones/cursos/58-thumb.png","_img/icones/cursos/236-thumb.png","_img/icones/cursos/222-thumb.png","_img/icones/cursos/53-thumb.png","_img/icones/cursos/220-thumb.png","_img/icones/cursos/255-thumb.png","_img/icones/cursos/131-thumb.png","_img/icones/cursos/66-thumb.png","_img/icones/cursos/126-thumb.png","_img/icones/cursos/276-thumb.png","_img/icones/cursos/123-thumb.png","_img/icones/cursos/513-thumb.png","_img/icones/cursos/169-thumb.png","_img/icones/cursos/149-thumb.png","_img/icones/cursos/355-thumb.png","_img/icones/cursos/1-thumb.png","_img/icones/cursos/38-thumb.png","_img/icones/cursos/238-thumb.png","_img/icones/cursos/198-thumb.png","_img/icones/cursos/734-thumb.png","_img/icones/cursos/51-thumb.png","_img/icones/cursos/64-thumb.png","_img/icones/cursos/104-thumb.png","_img/icones/cursos/135-thumb.png","_img/icones/cursos/107-thumb.png","_img/icones/cursos/94-thumb.png","_img/icones/cursos/396-thumb.png","_img/icones/cursos/192-thumb.png","_img/icones/cursos/133-thumb.png","_img/icones/cursos/183-thumb.png","_img/icones/cursos/163-thumb.png","_img/icones/cursos/235-thumb.png","_img/icones/cursos/263-thumb.png","_img/icones/cursos/317-thumb.png","_img/icones/cursos/162-thumb.png","_img/icones/cursos/568-thumb.png","_img/icones/cursos/93-thumb.png","_img/icones/cursos/242-thumb.png","_img/icones/cursos/72-thumb.png","_img/icones/cursos/240-thumb.png","_img/icones/cursos/6-thumb.png","_img/icones/cursos/69-thumb.png","_img/icones/cursos/105-thumb.png","_img/icones/cursos/87-thumb.png","_img/icones/cursos/316-thumb.png","_img/icones/cursos/124-thumb.png","_img/icones/cursos/78-thumb.png","_img/icones/cursos/102-thumb.png","_img/icones/cursos/70-thumb.png","_img/icones/cursos/52-thumb.png","_img/icones/cursos/156-thumb.png","_img/icones/cursos/90-thumb.png","_img/icones/cursos/41-thumb.png","_img/icones/cursos/77-thumb.png","_img/icones/cursos/23-thumb.png","_img/icones/cursos/15-thumb.png","_img/icones/cursos/334-thumb.png","_img/icones/cursos/541-thumb.png","_img/icones/cursos/270-thumb.png","_img/icones/cursos/560-thumb.png","_img/icones/cursos/59-thumb.png","_img/icones/cursos/770-thumb.png","_img/icones/cursos/74-thumb.png","_img/icones/cursos/146-thumb.png","_img/icones/cursos/80-thumb.png","_img/icones/cursos/91-thumb.png","_img/icones/cursos/62-thumb.png","_img/icones/cursos/43-thumb.png","_img/icones/cursos/98-thumb.png","_img/icones/cursos/426-thumb.png","_img/icones/cursos/176-thumb.png","_img/icones/cursos/100-thumb.png","_img/icones/cursos/202-thumb.png","_img/icones/cursos/19-thumb.png","_img/icones/cursos/619-thumb.png","_img/icones/cursos/265-thumb.png","_img/icones/cursos/28-thumb.png","_img/icones/cursos/57-thumb.png","_img/icones/cursos/144-thumb.png","_img/icones/cursos/128-thumb.png","_img/icones/cursos/17-thumb.png","_img/icones/cursos/99-thumb.png","_img/icones/cursos/594-thumb.png","_img/icones/cursos/35-thumb.png","_img/icones/cursos/193-thumb.png","_img/icones/cursos/25-thumb.png","_img/icones/cursos/164-thumb.png","_img/icones/cursos/473-thumb.png","_img/icones/cursos/201-thumb.png","_img/icones/cursos/441-thumb.png","_img/icones/cursos/775-thumb.png","_img/icones/cursos/130-thumb.png","_img/icones/cursos/251-thumb.png","_img/icones/cursos/33-thumb.png","_img/icones/cursos/44-thumb.png","_img/icones/cursos/18-thumb.png","_img/icones/cursos/129-thumb.png","_img/icones/cursos/562-thumb.png","_img/icones/cursos/50-thumb.png","_img/icones/cursos/216-thumb.png","_img/icones/cursos/705-thumb.png","_img/icones/cursos/82-thumb.png","_img/icones/cursos/284-thumb.png","_img/icones/cursos/103-thumb.png","_img/icones/cursos/60-thumb.png","_img/icones/cursos/34-thumb.png","_img/icones/cursos/5-thumb.png","_img/icones/cursos/49-thumb.png","_img/icones/cursos/10-thumb.png","_img/icones/cursos/590-thumb.png","_img/icones/cursos/268-thumb.png","_img/icones/cursos/79-thumb.png","_img/icones/cursos/148-thumb.png","_img/icones/cursos/12-thumb.png","_img/icones/cursos/243-thumb.png","_img/icones/cursos/20-thumb.png","_img/icones/cursos/203-thumb.png","_img/icones/cursos/26-thumb.png","_img/icones/cursos/182-thumb.png","_img/icones/cursos/31-thumb.png","_img/icones/cursos/16-thumb.png","_img/icones/cursos/24-thumb.png","_img/icones/cursos/280-thumb.png","_img/icones/cursos/83-thumb.png","_img/icones/cursos/101-thumb.png","_img/icones/cursos/221-thumb.png","_img/icones/cursos/161-thumb.png","_img/icones/cursos/7-thumb.png","_img/icones/cursos/234-thumb.png","_img/icones/cursos/37-thumb.png","_img/icones/cursos/14-thumb.png","_img/icones/cursos/199-thumb.png","_img/icones/cursos/45-thumb.png","_img/icones/cursos/771-thumb.png","_img/icones/cursos/8-thumb.png","_img/icones/cursos/217-thumb.png","_img/icones/cursos/239-thumb.png","_img/icones/cursos/134-thumb.png","_img/icones/cursos/56-thumb.png","_img/icones/cursos/84-thumb.png","_img/icones/cursos/710-thumb.png","_img/icones/cursos/754-thumb.png","_img/icones/cursos/214-thumb.png","_img/icones/cursos/599-thumb.png","_img/icones/cursos/154-thumb.png","_img/icones/cursos/89-thumb.png","_img/icones/cursos/307-thumb.png","_img/icones/cursos/30-thumb.png","_img/icones/cursos/264-thumb.png","_img/icones/cursos/278-thumb.png","_img/icones/cursos/29-thumb.png","_img/icones/cursos/54-thumb.png","_img/icones/cursos/71-thumb.png","_img/icones/cursos/55-thumb.png","_img/icones/cursos/36-thumb.png","_img/icones/cursos/76-thumb.png","_img/icones/cursos/196-thumb.png","_img/icones/cursos/168-thumb.png","_img/icones/cursos/42-thumb.png","_img/icones/cursos/27-thumb.png","_img/icones/cursos/48-thumb.png","_img/icones/cursos/254-thumb.png","_img/icones/cursos/39-thumb.png","_img/icones/cursos/136-thumb.png",    ];

    // passa um array com as thumbs e tempo entre animações      
    GridAnimadoBagual(thumbs, 1000);
  </script>
  <script type="text/javascript">
    localStorage.clear();
    let teste_de_navegador

    $(document).ready(function() {

      navigator.sayswho = (function() {
        var ua = navigator.userAgent,
          tem,
          M = ua.match(/(opera|chrome|safari|firefox|msie|trident(?=\/))\/?\s*(\d+)/i) || [];
        if (/trident/i.test(M[1])) {
          tem = /\brv[ :]+(\d+)/g.exec(ua) || [];
          return 'IE ' + (tem[1] || '');
        }
        if (M[1] === 'Chrome') {
          tem = ua.match(/\b(OPR|Edge)\/(\d+)/);
          if (tem != null) return tem.slice(1).join(' ').replace('OPR', 'Opera');
        }
        M = M[2] ? [M[1], M[2]] : [navigator.appName, navigator.appVersion, '-?'];
        if ((tem = ua.match(/version\/(\d+)/i)) != null) M.splice(1, 1, tem[1]);
        return M.join(' ');
      })();

      teste_de_navegador = navigator.sayswho.split(" ");

      if (teste_de_navegador[0] == 'Chrome') {
        if (check_chrome_ua()) {
          $("#fechar").html("Para fechar utilize as teclas ALT + F4");
        }
      }

      if (teste_de_navegador[0] == 'MSIE' && teste_de_navegador[1] < 10) {
        var html = '<div class="alert alert-warning" style="margin-top: 15px; line-height: 1.1;"><small><strong>Alerta!!</strong> Você está utilizando uma versão desatualizada do navegador, recomendamos que atualize o seu navegador para uma melhor experiência de nosso método de ensino. <a href="http://www.updateyourbrowser.net/pt" target="_blank">Clique aqui para atualizar</a></small></div>'
        $("#alert-navegador").html(html);
      } else {
        $("#alert-navegador").remove();
      }

      fetch('chkl.php');

    });
  </script>
    <div class="clearfix">
    </div>
            <script type="text/javascript">
            var adblock = true;
        </script>
        <script type="text/javascript" src="_inc/js/adframe.js"></script>
        <script type="text/javascript">
            if (adblock) {
                swal({<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="minimal-ui, width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

    <title>Ouro Moderno - Versão 5.17.4</title>
    <link rel='shortcut icon' type='image/x-icon' href='favicon.ico' />
    <link rel='icon' href='favicon.ico' />
    <link href="_css/reset.css?v=5.17.4" type="text/css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="_assets/normalize.css">
        <link rel="stylesheet" href="_assets/bootstrap/bootstrap.min.css">
    <link rel="stylesheet" href="_assets/font-awesome/css/font-awesome.min.css">

    
        <script src="_inc/js/jquery-3.2.1.min.js"></script>
        <script src="_assets/bootstrap/popper.min.js"></script>
        <script src="_assets/bootstrap/bootstrap.min.js"></script>
        <link href="_css/login.css?v=5.17.4" type="text/css" rel="stylesheet" />
        <link href="_css/login.custom.css?v=5.17.4" type="text/css" rel="stylesheet" />

    
    <script src="_assets/core.js"></script>
    <script src="_assets/sweetalert2.all.min.js"></script>
    <script src="_inc/js/alertas.js"></script>
    <script src="_inc/js/main.js"></script>
    <script type="text/javascript" src="_inc/js/funcoes.js?v=5.17.4"></script>

    <link href="_css/temas/light.css?v=5.17.4" type="text/css" rel="stylesheet" /></head>

<body id="pag-login" class="tema-light   ">
    <link href="_css/loader-wrapper.css" type="text/css" rel="stylesheet">
<script type="text/javascript">
    $(document).ready(function() {
        $('body').addClass('loaded');
    });
</script>
<div id="loader-wrapper">
    <div id="loader"></div>
    <div class="loader-section section-left"></div>
    <div class="loader-section section-right"></div>
</div><section class="login-block">
  <a href="javascript:void(0);" onclick="fechar()" id="fechar">Fechar</a>

      <div id="idioma_login" class="dropdown">
      <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <i class="fa fa-language" aria-hidden="true"></i>
      </button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <button type="button" class="dropdown-item active" onclick="set_language('pt')"><img src="_img/icones/idiomas/pt.png"> Português</button>
        <button type="button" class="dropdown-item " onclick="set_language('es')"><img src="_img/icones/idiomas/es.png"> Espanhol</button>

      </div>
    </div>
  
    <div class="container" >
    <div class="row justify-content-center">
      <div class="col-md-4 login-sec row m-0" id="login-sec">
        <div class="my-auto">

          <img src="_img/_liquido/custom/logoLogin.png" alt="Logo" class="w-100 img-fluid" />


                      <style>
              #login-sec .form-group {
                position: relative;
                margin-bottom: 1.5rem;
              }

              #login-sec .form-control {
                padding: 0 !important;
                padding-bottom: 10px;
                height: auto !important;
                border-radius: 0 !important;
                border: 0;
                border-bottom: solid 1px #000;
              }

              #login-sec .form-control:hover,
              #login-sec .form-control:focus {
                box-shadow: none;
              }

              #login-sec .form-control-placeholder {
                position: absolute;
                top: 0;
                left: 40px;
                padding: 0;
                transition: all 200ms;
                opacity: 0.5;
              }

              #login-sec .form-control:focus+.form-control-placeholder,
              #login-sec .form-control:valid+.form-control-placeholder {
                font-size: 75%;
                transform: translate3d(0, -100%, 0);
                opacity: 1;
              }
            </style>
          
          <h2 class="text-center">Digite seu usuário e senha</h2>
                      <form class="login-form mt-4" action="logar.php?acao=logar" method="post" autocomplete="off">
              <div class="form-group">
                <div class="loading"></div>
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-user" aria-hidden="true"></i></span>
                  </div>
                  <input type="text" name="aluno" id="aluno" class="campo form-control" autocomplete="off" required>
                  <label class="form-control-placeholder" for="aluno">Usuário</label>
                </div>
              </div>
              <div class="form-group">
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-key" aria-hidden="true"></i></span>
                  </div>
                  <input type="password" name="senha" id="senha" class="campo form-control" autocomplete="new-password" required>
                  <label class="form-control-placeholder" for="senha">Senha</label>
                </div>
              </div>
              <div class="form-group text-center">
                <button type="submit" class="btn btn-primary  btn-login rounded-pill mt-1 px-5">Acessar <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></button>
              </div>
            </form>
                    <div id="alert-navegador"></div>
        </div>
      </div>

      
        <div class="col-md-8 banner-sec">

          <div id="carouselLogin" class="carousel slide" data-ride="carousel" data-interval="10000">
            <!--carousel-->
            <ol class="carousel-indicators">
                              <li data-target="#carouselLogin" data-slide-to="0" class="active"></li>

                                                              <li data-target="#carouselLogin"  data-slide-to="1"></li>
                  <li data-target="#carouselLogin" data-slide-to="2"></li>
                  <li data-target="#carouselLogin" data-slide-to="3"></li>
                  <li data-target="#carouselLogin" data-slide-to="4"></li>
                  <li data-target="#carouselLogin" data-slide-to="5"></li>
                  <li data-target="#carouselLogin" data-slide-to="6"></li>
                            </ol>
            <div class="carousel-inner" role="listbox">
                              
                  <div class="carousel-item active">

                    <div class="GridAnimadoBagual">
                      <img class="img-fluid" src="_img/login_slide/1.jpeg" alt="">
                      <div id="GridAnimadoBagual">
                        <div class="coluna" id="column-1">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/85-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/2-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/138-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/155-thumb.png')"></div>
                          
                        </div>
                        <div class="coluna" id="column-2">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/561-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/88-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/360-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/65-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-3">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/252-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/47-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/127-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/4-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-4">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/40-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/75-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/266-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/159-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-5">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/46-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/106-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/639-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/628-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-6">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/139-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/73-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/61-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/271-thumb.png')"></div>
                                                  </div>
                      </div>
                    </div>
                  </div>

                              
              
                                <div class="carousel-item ">
                    <img class="img-fluid" src="_img/login_slide/2.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/3.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/4.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/5.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/6.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/7.jpg?v=1" alt="">
                  </div>
                
            </div>
          </div>
        </div>
          </div>

</section>
<script type="text/javascript">
  $('form').submit(function(event) {
    $('body').removeClass('loaded');
  });
</script>
  <link rel="stylesheet" href="_assets/gridanimadobagual/jquery.gridanimadobagual.css">
  <script src="_assets/gridanimadobagual/jquery.gridanimadobagual.js"></script>

  <script type="text/javascript">
    // popula a variavel 'imagens_1' com as thumb dos cursos  
    var thumbs = [
      "_img/icones/cursos/85-thumb.png","_img/icones/cursos/2-thumb.png","_img/icones/cursos/138-thumb.png","_img/icones/cursos/155-thumb.png","_img/icones/cursos/561-thumb.png","_img/icones/cursos/88-thumb.png","_img/icones/cursos/360-thumb.png","_img/icones/cursos/65-thumb.png","_img/icones/cursos/252-thumb.png","_img/icones/cursos/47-thumb.png","_img/icones/cursos/127-thumb.png","_img/icones/cursos/4-thumb.png","_img/icones/cursos/40-thumb.png","_img/icones/cursos/75-thumb.png","_img/icones/cursos/266-thumb.png","_img/icones/cursos/159-thumb.png","_img/icones/cursos/46-thumb.png","_img/icones/cursos/106-thumb.png","_img/icones/cursos/639-thumb.png","_img/icones/cursos/628-thumb.png","_img/icones/cursos/139-thumb.png","_img/icones/cursos/73-thumb.png","_img/icones/cursos/61-thumb.png","_img/icones/cursos/271-thumb.png","_img/icones/cursos/153-thumb.png","_img/icones/cursos/21-thumb.png","_img/icones/cursos/627-thumb.png","_img/icones/cursos/218-thumb.png","_img/icones/cursos/195-thumb.png","_img/icones/cursos/63-thumb.png","_img/icones/cursos/92-thumb.png","_img/icones/cursos/167-thumb.png","_img/icones/cursos/11-thumb.png","_img/icones/cursos/67-thumb.png","_img/icones/cursos/68-thumb.png","_img/icones/cursos/237-thumb.png","_img/icones/cursos/32-thumb.png","_img/icones/cursos/659-thumb.png","_img/icones/cursos/281-thumb.png","_img/icones/cursos/13-thumb.png","_img/icones/cursos/200-thumb.png","_img/icones/cursos/160-thumb.png","_img/icones/cursos/253-thumb.png","_img/icones/cursos/3-thumb.png","_img/icones/cursos/197-thumb.png","_img/icones/cursos/207-thumb.png","_img/icones/cursos/81-thumb.png","_img/icones/cursos/58-thumb.png","_img/icones/cursos/236-thumb.png","_img/icones/cursos/222-thumb.png","_img/icones/cursos/53-thumb.png","_img/icones/cursos/220-thumb.png","_img/icones/cursos/255-thumb.png","_img/icones/cursos/131-thumb.png","_img/icones/cursos/66-thumb.png","_img/icones/cursos/126-thumb.png","_img/icones/cursos/276-thumb.png","_img/icones/cursos/123-thumb.png","_img/icones/cursos/513-thumb.png","_img/icones/cursos/169-thumb.png","_img/icones/cursos/149-thumb.png","_img/icones/cursos/355-thumb.png","_img/icones/cursos/1-thumb.png","_img/icones/cursos/38-thumb.png","_img/icones/cursos/238-thumb.png","_img/icones/cursos/198-thumb.png","_img/icones/cursos/734-thumb.png","_img/icones/cursos/51-thumb.png","_img/icones/cursos/64-thumb.png","_img/icones/cursos/104-thumb.png","_img/icones/cursos/135-thumb.png","_img/icones/cursos/107-thumb.png","_img/icones/cursos/94-thumb.png","_img/icones/cursos/396-thumb.png","_img/icones/cursos/192-thumb.png","_img/icones/cursos/133-thumb.png","_img/icones/cursos/183-thumb.png","_img/icones/cursos/163-thumb.png","_img/icones/cursos/235-thumb.png","_img/icones/cursos/263-thumb.png","_img/icones/cursos/317-thumb.png","_img/icones/cursos/162-thumb.png","_img/icones/cursos/568-thumb.png","_img/icones/cursos/93-thumb.png","_img/icones/cursos/242-thumb.png","_img/icones/cursos/72-thumb.png","_img/icones/cursos/240-thumb.png","_img/icones/cursos/6-thumb.png","_img/icones/cursos/69-thumb.png","_img/icones/cursos/105-thumb.png","_img/icones/cursos/87-thumb.png","_img/icones/cursos/316-thumb.png","_img/icones/cursos/124-thumb.png","_img/icones/cursos/78-thumb.png","_img/icones/cursos/102-thumb.png","_img/icones/cursos/70-thumb.png","_img/icones/cursos/52-thumb.png","_img/icones/cursos/156-thumb.png","_img/icones/cursos/90-thumb.png","_img/icones/cursos/41-thumb.png","_img/icones/cursos/77-thumb.png","_img/icones/cursos/23-thumb.png","_img/icones/cursos/15-thumb.png","_img/icones/cursos/334-thumb.png","_img/icones/cursos/541-thumb.png","_img/icones/cursos/270-thumb.png","_img/icones/cursos/560-thumb.png","_img/icones/cursos/59-thumb.png","_img/icones/cursos/770-thumb.png","_img/icones/cursos/74-thumb.png","_img/icones/cursos/146-thumb.png","_img/icones/cursos/80-thumb.png","_img/icones/cursos/91-thumb.png","_img/icones/cursos/62-thumb.png","_img/icones/cursos/43-thumb.png","_img/icones/cursos/98-thumb.png","_img/icones/cursos/426-thumb.png","_img/icones/cursos/176-thumb.png","_img/icones/cursos/100-thumb.png","_img/icones/cursos/202-thumb.png","_img/icones/cursos/19-thumb.png","_img/icones/cursos/619-thumb.png","_img/icones/cursos/265-thumb.png","_img/icones/cursos/28-thumb.png","_img/icones/cursos/57-thumb.png","_img/icones/cursos/144-thumb.png","_img/icones/cursos/128-thumb.png","_img/icones/cursos/17-thumb.png","_img/icones/cursos/99-thumb.png","_img/icones/cursos/594-thumb.png","_img/icones/cursos/35-thumb.png","_img/icones/cursos/193-thumb.png","_img/icones/cursos/25-thumb.png","_img/icones/cursos/164-thumb.png","_img/icones/cursos/473-thumb.png","_img/icones/cursos/201-thumb.png","_img/icones/cursos/441-thumb.png","_img/icones/cursos/775-thumb.png","_img/icones/cursos/130-thumb.png","_img/icones/cursos/251-thumb.png","_img/icones/cursos/33-thumb.png","_img/icones/cursos/44-thumb.png","_img/icones/cursos/18-thumb.png","_img/icones/cursos/129-thumb.png","_img/icones/cursos/562-thumb.png","_img/icones/cursos/50-thumb.png","_img/icones/cursos/216-thumb.png","_img/icones/cursos/705-thumb.png","_img/icones/cursos/82-thumb.png","_img/icones/cursos/284-thumb.png","_img/icones/cursos/103-thumb.png","_img/icones/cursos/60-thumb.png","_img/icones/cursos/34-thumb.png","_img/icones/cursos/5-thumb.png","_img/icones/cursos/49-thumb.png","_img/icones/cursos/10-thumb.png","_img/icones/cursos/590-thumb.png","_img/icones/cursos/268-thumb.png","_img/icones/cursos/79-thumb.png","_img/icones/cursos/148-thumb.png","_img/icones/cursos/12-thumb.png","_img/icones/cursos/243-thumb.png","_img/icones/cursos/20-thumb.png","_img/icones/cursos/203-thumb.png","_img/icones/cursos/26-thumb.png","_img/icones/cursos/182-thumb.png","_img/icones/cursos/31-thumb.png","_img/icones/cursos/16-thumb.png","_img/icones/cursos/24-thumb.png","_img/icones/cursos/280-thumb.png","_img/icones/cursos/83-thumb.png","_img/icones/cursos/101-thumb.png","_img/icones/cursos/221-thumb.png","_img/icones/cursos/161-thumb.png","_img/icones/cursos/7-thumb.png","_img/icones/cursos/234-thumb.png","_img/icones/cursos/37-thumb.png","_img/icones/cursos/14-thumb.png","_img/icones/cursos/199-thumb.png","_img/icones/cursos/45-thumb.png","_img/icones/cursos/771-thumb.png","_img/icones/cursos/8-thumb.png","_img/icones/cursos/217-thumb.png","_img/icones/cursos/239-thumb.png","_img/icones/cursos/134-thumb.png","_img/icones/cursos/56-thumb.png","_img/icones/cursos/84-thumb.png","_img/icones/cursos/710-thumb.png","_img/icones/cursos/754-thumb.png","_img/icones/cursos/214-thumb.png","_img/icones/cursos/599-thumb.png","_img/icones/cursos/154-thumb.png","_img/icones/cursos/89-thumb.png","_img/icones/cursos/307-thumb.png","_img/icones/cursos/30-thumb.png","_img/icones/cursos/264-thumb.png","_img/icones/cursos/278-thumb.png","_img/icones/cursos/29-thumb.png","_img/icones/cursos/54-thumb.png","_img/icones/cursos/71-thumb.png","_img/icones/cursos/55-thumb.png","_img/icones/cursos/36-thumb.png","_img/icones/cursos/76-thumb.png","_img/icones/cursos/196-thumb.png","_img/icones/cursos/168-thumb.png","_img/icones/cursos/42-thumb.png","_img/icones/cursos/27-thumb.png","_img/icones/cursos/48-thumb.png","_img/icones/cursos/254-thumb.png","_img/icones/cursos/39-thumb.png","_img/icones/cursos/136-thumb.png",    ];

    // passa um array com as thumbs e tempo entre animações      
    GridAnimadoBagual(thumbs, 1000);
  </script>
  <script type="text/javascript">
    localStorage.clear();
    let teste_de_navegador

    $(document).ready(function() {

      navigator.sayswho = (function() {
        var ua = navigator.userAgent,
          tem,
          M = ua.match(/(opera|chrome|safari|firefox|msie|trident(?=\/))\/?\s*(\d+)/i) || [];
        if (/trident/i.test(M[1])) {
          tem = /\brv[ :]+(\d+)/g.exec(ua) || [];
          return 'IE ' + (tem[1] || '');
        }
        if (M[1] === 'Chrome') {
          tem = ua.match(/\b(OPR|Edge)\/(\d+)/);
          if (tem != null) return tem.slice(1).join(' ').replace('OPR', 'Opera');
        }
        M = M[2] ? [M[1], M[2]] : [navigator.appName, navigator.appVersion, '-?'];
        if ((tem = ua.match(/version\/(\d+)/i)) != null) M.splice(1, 1, tem[1]);
        return M.join(' ');
      })();

      teste_de_navegador = navigator.sayswho.split(" ");

      if (teste_de_navegador[0] == 'Chrome') {
        if (check_chrome_ua()) {
          $("#fechar").html("Para fechar utilize as teclas ALT + F4");
        }
      }

      if (teste_de_navegador[0] == 'MSIE' && teste_de_navegador[1] < 10) {
        var html = '<div class="alert alert-warning" style="margin-top: 15px; line-height: 1.1;"><small><strong>Alerta!!</strong> Você está utilizando uma versão desatualizada do navegador, recomendamos que atualize o seu navegador para uma melhor experiência de nosso método de ensino. <a href="http://www.updateyourbrowser.net/pt" target="_blank">Clique aqui para atualizar</a></small></div>'
        $("#alert-navegador").html(html);
      } else {
        $("#alert-navegador").remove();
      }

      fetch('chkl.php');

    });
  </script>
    <div class="clearfix">
    </div>
            <script type="text/javascript">
            var adblock = true;
        </script>
        <script type="text/javascript" src="_inc/js/adframe.js"></script>
        <script type="text/javascript">
            if (adblock) {
                swal({
                    title: 'AdBlock Instalado',
                    html: 'AdBlock pode causar problemas na utilização do método. Favor desativar o AdBlock.',
                    type: 'error'
                })
            }
        </script>
        <div id="carregando" style="display: none;"></div>
</body>

</html><!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="minimal-ui, width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

    <title>Ouro Moderno - Versão 5.17.4</title>
    <link rel='shortcut icon' type='image/x-icon' href='favicon.ico' />
    <link rel='icon' href='favicon.ico' />
    <link href="_css/reset.css?v=5.17.4" type="text/css" rel="stylesheet" />
    <link rel="stylesheet" type="text/css" href="_assets/normalize.css">
        <link rel="stylesheet" href="_assets/bootstrap/bootstrap.min.css">
    <link rel="stylesheet" href="_assets/font-awesome/css/font-awesome.min.css">

    
        <script src="_inc/js/jquery-3.2.1.min.js"></script>
        <script src="_assets/bootstrap/popper.min.js"></script>
        <script src="_assets/bootstrap/bootstrap.min.js"></script>
        <link href="_css/login.css?v=5.17.4" type="text/css" rel="stylesheet" />
        <link href="_css/login.custom.css?v=5.17.4" type="text/css" rel="stylesheet" />

    
    <script src="_assets/core.js"></script>
    <script src="_assets/sweetalert2.all.min.js"></script>
    <script src="_inc/js/alertas.js"></script>
    <script src="_inc/js/main.js"></script>
    <script type="text/javascript" src="_inc/js/funcoes.js?v=5.17.4"></script>

    <link href="_css/temas/light.css?v=5.17.4" type="text/css" rel="stylesheet" /></head>

<body id="pag-login" class="tema-light   ">
    <link href="_css/loader-wrapper.css" type="text/css" rel="stylesheet">
<script type="text/javascript">
    $(document).ready(function() {
        $('body').addClass('loaded');
    });
</script>
<div id="loader-wrapper">
    <div id="loader"></div>
    <div class="loader-section section-left"></div>
    <div class="loader-section section-right"></div>
</div><section class="login-block">
  <a href="javascript:void(0);" onclick="fechar()" id="fechar">Fechar</a>

      <div id="idioma_login" class="dropdown">
      <button class="btn btn-primary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        <i class="fa fa-language" aria-hidden="true"></i>
      </button>
      <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <button type="button" class="dropdown-item active" onclick="set_language('pt')"><img src="_img/icones/idiomas/pt.png"> Português</button>
        <button type="button" class="dropdown-item " onclick="set_language('es')"><img src="_img/icones/idiomas/es.png"> Espanhol</button>

      </div>
    </div>
  
    <div class="container" >
    <div class="row justify-content-center">
      <div class="col-md-4 login-sec row m-0" id="login-sec">
        <div class="my-auto">

          <img src="_img/_liquido/custom/logoLogin.png" alt="Logo" class="w-100 img-fluid" />


                      <style>
              #login-sec .form-group {
                position: relative;
                margin-bottom: 1.5rem;
              }

              #login-sec .form-control {
                padding: 0 !important;
                padding-bottom: 10px;
                height: auto !important;
                border-radius: 0 !important;
                border: 0;
                border-bottom: solid 1px #000;
              }

              #login-sec .form-control:hover,
              #login-sec .form-control:focus {
                box-shadow: none;
              }

              #login-sec .form-control-placeholder {
                position: absolute;
                top: 0;
                left: 40px;
                padding: 0;
                transition: all 200ms;
                opacity: 0.5;
              }

              #login-sec .form-control:focus+.form-control-placeholder,
              #login-sec .form-control:valid+.form-control-placeholder {
                font-size: 75%;
                transform: translate3d(0, -100%, 0);
                opacity: 1;
              }
            </style>
          
          <h2 class="text-center">Digite seu usuário e senha</h2>
                      <form class="login-form mt-4" action="logar.php?acao=logar" method="post" autocomplete="off">
              <div class="form-group">
                <div class="loading"></div>
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-user" aria-hidden="true"></i></span>
                  </div>
                  <input type="text" name="aluno" id="aluno" class="campo form-control" autocomplete="off" required>
                  <label class="form-control-placeholder" for="aluno">Usuário</label>
                </div>
              </div>
              <div class="form-group">
                <div class="input-group mb-3">
                  <div class="input-group-prepend">
                    <span class="input-group-text" id="basic-addon1"><i class="fa fa-key" aria-hidden="true"></i></span>
                  </div>
                  <input type="password" name="senha" id="senha" class="campo form-control" autocomplete="new-password" required>
                  <label class="form-control-placeholder" for="senha">Senha</label>
                </div>
              </div>
              <div class="form-group text-center">
                <button type="submit" class="btn btn-primary  btn-login rounded-pill mt-1 px-5">Acessar <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></button>
              </div>
            </form>
                    <div id="alert-navegador"></div>
        </div>
      </div>

      
        <div class="col-md-8 banner-sec">

          <div id="carouselLogin" class="carousel slide" data-ride="carousel" data-interval="10000">
            <!--carousel-->
            <ol class="carousel-indicators">
                              <li data-target="#carouselLogin" data-slide-to="0" class="active"></li>

                                                              <li data-target="#carouselLogin"  data-slide-to="1"></li>
                  <li data-target="#carouselLogin" data-slide-to="2"></li>
                  <li data-target="#carouselLogin" data-slide-to="3"></li>
                  <li data-target="#carouselLogin" data-slide-to="4"></li>
                  <li data-target="#carouselLogin" data-slide-to="5"></li>
                  <li data-target="#carouselLogin" data-slide-to="6"></li>
                            </ol>
            <div class="carousel-inner" role="listbox">
                              
                  <div class="carousel-item active">

                    <div class="GridAnimadoBagual">
                      <img class="img-fluid" src="_img/login_slide/1.jpeg" alt="">
                      <div id="GridAnimadoBagual">
                        <div class="coluna" id="column-1">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/85-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/2-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/138-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/155-thumb.png')"></div>
                          
                        </div>
                        <div class="coluna" id="column-2">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/561-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/88-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/360-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/65-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-3">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/252-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/47-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/127-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/4-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-4">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/40-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/75-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/266-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/159-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-5">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/46-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/106-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/639-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/628-thumb.png')"></div>
                                                  </div>
                        <div class="coluna" id="column-6">
                                                      <div class="linha container-1" style="background-image: url('_img/icones/cursos/139-thumb.png')"></div>
                                                      <div class="linha container-2" style="background-image: url('_img/icones/cursos/73-thumb.png')"></div>
                                                      <div class="linha container-3" style="background-image: url('_img/icones/cursos/61-thumb.png')"></div>
                                                      <div class="linha container-4" style="background-image: url('_img/icones/cursos/271-thumb.png')"></div>
                                                  </div>
                      </div>
                    </div>
                  </div>

                              
              
                                <div class="carousel-item ">
                    <img class="img-fluid" src="_img/login_slide/2.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/3.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/4.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/5.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/6.jpg?v=1" alt="">
                  </div>
                  <div class="carousel-item">
                    <img class="img-fluid" src="_img/login_slide/7.jpg?v=1" alt="">
                  </div>
                
            </div>
          </div>
        </div>
          </div>

</section>
<script type="text/javascript">
  $('form').submit(function(event) {
    $('body').removeClass('loaded');
  });
</script>
  <link rel="stylesheet" href="_assets/gridanimadobagual/jquery.gridanimadobagual.css">
  <script src="_assets/gridanimadobagual/jquery.gridanimadobagual.js"></script>

  <script type="text/javascript">
    // popula a variavel 'imagens_1' com as thumb dos cursos  
    var thumbs = [
      "_img/icones/cursos/85-thumb.png","_img/icones/cursos/2-thumb.png","_img/icones/cursos/138-thumb.png","_img/icones/cursos/155-thumb.png","_img/icones/cursos/561-thumb.png","_img/icones/cursos/88-thumb.png","_img/icones/cursos/360-thumb.png","_img/icones/cursos/65-thumb.png","_img/icones/cursos/252-thumb.png","_img/icones/cursos/47-thumb.png","_img/icones/cursos/127-thumb.png","_img/icones/cursos/4-thumb.png","_img/icones/cursos/40-thumb.png","_img/icones/cursos/75-thumb.png","_img/icones/cursos/266-thumb.png","_img/icones/cursos/159-thumb.png","_img/icones/cursos/46-thumb.png","_img/icones/cursos/106-thumb.png","_img/icones/cursos/639-thumb.png","_img/icones/cursos/628-thumb.png","_img/icones/cursos/139-thumb.png","_img/icones/cursos/73-thumb.png","_img/icones/cursos/61-thumb.png","_img/icones/cursos/271-thumb.png","_img/icones/cursos/153-thumb.png","_img/icones/cursos/21-thumb.png","_img/icones/cursos/627-thumb.png","_img/icones/cursos/218-thumb.png","_img/icones/cursos/195-thumb.png","_img/icones/cursos/63-thumb.png","_img/icones/cursos/92-thumb.png","_img/icones/cursos/167-thumb.png","_img/icones/cursos/11-thumb.png","_img/icones/cursos/67-thumb.png","_img/icones/cursos/68-thumb.png","_img/icones/cursos/237-thumb.png","_img/icones/cursos/32-thumb.png","_img/icones/cursos/659-thumb.png","_img/icones/cursos/281-thumb.png","_img/icones/cursos/13-thumb.png","_img/icones/cursos/200-thumb.png","_img/icones/cursos/160-thumb.png","_img/icones/cursos/253-thumb.png","_img/icones/cursos/3-thumb.png","_img/icones/cursos/197-thumb.png","_img/icones/cursos/207-thumb.png","_img/icones/cursos/81-thumb.png","_img/icones/cursos/58-thumb.png","_img/icones/cursos/236-thumb.png","_img/icones/cursos/222-thumb.png","_img/icones/cursos/53-thumb.png","_img/icones/cursos/220-thumb.png","_img/icones/cursos/255-thumb.png","_img/icones/cursos/131-thumb.png","_img/icones/cursos/66-thumb.png","_img/icones/cursos/126-thumb.png","_img/icones/cursos/276-thumb.png","_img/icones/cursos/123-thumb.png","_img/icones/cursos/513-thumb.png","_img/icones/cursos/169-thumb.png","_img/icones/cursos/149-thumb.png","_img/icones/cursos/355-thumb.png","_img/icones/cursos/1-thumb.png","_img/icones/cursos/38-thumb.png","_img/icones/cursos/238-thumb.png","_img/icones/cursos/198-thumb.png","_img/icones/cursos/734-thumb.png","_img/icones/cursos/51-thumb.png","_img/icones/cursos/64-thumb.png","_img/icones/cursos/104-thumb.png","_img/icones/cursos/135-thumb.png","_img/icones/cursos/107-thumb.png","_img/icones/cursos/94-thumb.png","_img/icones/cursos/396-thumb.png","_img/icones/cursos/192-thumb.png","_img/icones/cursos/133-thumb.png","_img/icones/cursos/183-thumb.png","_img/icones/cursos/163-thumb.png","_img/icones/cursos/235-thumb.png","_img/icones/cursos/263-thumb.png","_img/icones/cursos/317-thumb.png","_img/icones/cursos/162-thumb.png","_img/icones/cursos/568-thumb.png","_img/icones/cursos/93-thumb.png","_img/icones/cursos/242-thumb.png","_img/icones/cursos/72-thumb.png","_img/icones/cursos/240-thumb.png","_img/icones/cursos/6-thumb.png","_img/icones/cursos/69-thumb.png","_img/icones/cursos/105-thumb.png","_img/icones/cursos/87-thumb.png","_img/icones/cursos/316-thumb.png","_img/icones/cursos/124-thumb.png","_img/icones/cursos/78-thumb.png","_img/icones/cursos/102-thumb.png","_img/icones/cursos/70-thumb.png","_img/icones/cursos/52-thumb.png","_img/icones/cursos/156-thumb.png","_img/icones/cursos/90-thumb.png","_img/icones/cursos/41-thumb.png","_img/icones/cursos/77-thumb.png","_img/icones/cursos/23-thumb.png","_img/icones/cursos/15-thumb.png","_img/icones/cursos/334-thumb.png","_img/icones/cursos/541-thumb.png","_img/icones/cursos/270-thumb.png","_img/icones/cursos/560-thumb.png","_img/icones/cursos/59-thumb.png","_img/icones/cursos/770-thumb.png","_img/icones/cursos/74-thumb.png","_img/icones/cursos/146-thumb.png","_img/icones/cursos/80-thumb.png","_img/icones/cursos/91-thumb.png","_img/icones/cursos/62-thumb.png","_img/icones/cursos/43-thumb.png","_img/icones/cursos/98-thumb.png","_img/icones/cursos/426-thumb.png","_img/icones/cursos/176-thumb.png","_img/icones/cursos/100-thumb.png","_img/icones/cursos/202-thumb.png","_img/icones/cursos/19-thumb.png","_img/icones/cursos/619-thumb.png","_img/icones/cursos/265-thumb.png","_img/icones/cursos/28-thumb.png","_img/icones/cursos/57-thumb.png","_img/icones/cursos/144-thumb.png","_img/icones/cursos/128-thumb.png","_img/icones/cursos/17-thumb.png","_img/icones/cursos/99-thumb.png","_img/icones/cursos/594-thumb.png","_img/icones/cursos/35-thumb.png","_img/icones/cursos/193-thumb.png","_img/icones/cursos/25-thumb.png","_img/icones/cursos/164-thumb.png","_img/icones/cursos/473-thumb.png","_img/icones/cursos/201-thumb.png","_img/icones/cursos/441-thumb.png","_img/icones/cursos/775-thumb.png","_img/icones/cursos/130-thumb.png","_img/icones/cursos/251-thumb.png","_img/icones/cursos/33-thumb.png","_img/icones/cursos/44-thumb.png","_img/icones/cursos/18-thumb.png","_img/icones/cursos/129-thumb.png","_img/icones/cursos/562-thumb.png","_img/icones/cursos/50-thumb.png","_img/icones/cursos/216-thumb.png","_img/icones/cursos/705-thumb.png","_img/icones/cursos/82-thumb.png","_img/icones/cursos/284-thumb.png","_img/icones/cursos/103-thumb.png","_img/icones/cursos/60-thumb.png","_img/icones/cursos/34-thumb.png","_img/icones/cursos/5-thumb.png","_img/icones/cursos/49-thumb.png","_img/icones/cursos/10-thumb.png","_img/icones/cursos/590-thumb.png","_img/icones/cursos/268-thumb.png","_img/icones/cursos/79-thumb.png","_img/icones/cursos/148-thumb.png","_img/icones/cursos/12-thumb.png","_img/icones/cursos/243-thumb.png","_img/icones/cursos/20-thumb.png","_img/icones/cursos/203-thumb.png","_img/icones/cursos/26-thumb.png","_img/icones/cursos/182-thumb.png","_img/icones/cursos/31-thumb.png","_img/icones/cursos/16-thumb.png","_img/icones/cursos/24-thumb.png","_img/icones/cursos/280-thumb.png","_img/icones/cursos/83-thumb.png","_img/icones/cursos/101-thumb.png","_img/icones/cursos/221-thumb.png","_img/icones/cursos/161-thumb.png","_img/icones/cursos/7-thumb.png","_img/icones/cursos/234-thumb.png","_img/icones/cursos/37-thumb.png","_img/icones/cursos/14-thumb.png","_img/icones/cursos/199-thumb.png","_img/icones/cursos/45-thumb.png","_img/icones/cursos/771-thumb.png","_img/icones/cursos/8-thumb.png","_img/icones/cursos/217-thumb.png","_img/icones/cursos/239-thumb.png","_img/icones/cursos/134-thumb.png","_img/icones/cursos/56-thumb.png","_img/icones/cursos/84-thumb.png","_img/icones/cursos/710-thumb.png","_img/icones/cursos/754-thumb.png","_img/icones/cursos/214-thumb.png","_img/icones/cursos/599-thumb.png","_img/icones/cursos/154-thumb.png","_img/icones/cursos/89-thumb.png","_img/icones/cursos/307-thumb.png","_img/icones/cursos/30-thumb.png","_img/icones/cursos/264-thumb.png","_img/icones/cursos/278-thumb.png","_img/icones/cursos/29-thumb.png","_img/icones/cursos/54-thumb.png","_img/icones/cursos/71-thumb.png","_img/icones/cursos/55-thumb.png","_img/icones/cursos/36-thumb.png","_img/icones/cursos/76-thumb.png","_img/icones/cursos/196-thumb.png","_img/icones/cursos/168-thumb.png","_img/icones/cursos/42-thumb.png","_img/icones/cursos/27-thumb.png","_img/icones/cursos/48-thumb.png","_img/icones/cursos/254-thumb.png","_img/icones/cursos/39-thumb.png","_img/icones/cursos/136-thumb.png",    ];

    // passa um array com as thumbs e tempo entre animações      
    GridAnimadoBagual(thumbs, 1000);
  </script>
  <script type="text/javascript">
    localStorage.clear();
    let teste_de_navegador

    $(document).ready(function() {

      navigator.sayswho = (function() {
        var ua = navigator.userAgent,
          tem,
          M = ua.match(/(opera|chrome|safari|firefox|msie|trident(?=\/))\/?\s*(\d+)/i) || [];
        if (/trident/i.test(M[1])) {
          tem = /\brv[ :]+(\d+)/g.exec(ua) || [];
          return 'IE ' + (tem[1] || '');
        }
        if (M[1] === 'Chrome') {
          tem = ua.match(/\b(OPR|Edge)\/(\d+)/);
          if (tem != null) return tem.slice(1).join(' ').replace('OPR', 'Opera');
        }
        M = M[2] ? [M[1], M[2]] : [navigator.appName, navigator.appVersion, '-?'];
        if ((tem = ua.match(/version\/(\d+)/i)) != null) M.splice(1, 1, tem[1]);
        return M.join(' ');
      })();

      teste_de_navegador = navigator.sayswho.split(" ");

      if (teste_de_navegador[0] == 'Chrome') {
        if (check_chrome_ua()) {
          $("#fechar").html("Para fechar utilize as teclas ALT + F4");
        }
      }

      if (teste_de_navegador[0] == 'MSIE' && teste_de_navegador[1] < 10) {
        var html = '<div class="alert alert-warning" style="margin-top: 15px; line-height: 1.1;"><small><strong>Alerta!!</strong> Você está utilizando uma versão desatualizada do navegador, recomendamos que atualize o seu navegador para uma melhor experiência de nosso método de ensino. <a href="http://www.updateyourbrowser.net/pt" target="_blank">Clique aqui para atualizar</a></small></div>'
        $("#alert-navegador").html(html);
      } else {
        $("#alert-navegador").remove();
      }

      fetch('chkl.php');

    });
  </script>
    <div class="clearfix">
    </div>
            <script type="text/javascript">
            var adblock = true;
        </script>
        <script type="text/javascript" src="_inc/js/adframe.js"></script>
        <script type="text/javascript">
            if (adblock) {
                swal({
                    title: 'AdBlock Instalado',
                    html: 'AdBlock pode causar problemas na utilização do método. Favor desativar o AdBlock.',
                    type: 'error'
                })
            }
        </script>
        <div id="carregando" style="display: none;"></div>
</body>

</html>
                    title: 'AdBlock Instalado',
                    html: 'AdBlock pode causar problemas na utilização do método. Favor desativar o AdBlock.',
                    type: 'error'
                })
            }
        </script>
        <div id="carregando" style="display: none;"></div>
</body>

</html>

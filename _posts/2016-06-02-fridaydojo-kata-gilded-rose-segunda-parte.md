---
layout: post
title: "#FridayDojo: Kata Gilded Rose (segunda parte)"
date: 2016-06-02 19:41:32.000000000 +02:00
type: post
published: true
status: publish
categories:
- General
tags: []
meta:
  _oembed_63669ef5bc4282177293b63eb3768b07: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:344px">     <div style="max-height:304px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_6e81ce8f5c1a3341fe463f8058a841b4: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:344px">     <div style="max-height:304px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_6e81ce8f5c1a3341fe463f8058a841b4: '1464889295'
  _oembed_54c32c454c9490d61904885ddb51b144: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:344px">     <div style="max-height:304px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _publicize_job_id: '23443861866'
  _oembed_f0e88f621a324699a4410213a5d60079: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:302px">     <div style="max-height:262px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_f0e88f621a324699a4410213a5d60079: '1464889298'
  _publicize_done_external: a:1:{s:7:"twitter";a:1:{i:6161812;s:57:"https://twitter.com/AgileAragon/status/738425360161738752";}}
  _publicize_done_6191518: '1'
  _wpas_done_6161812: '1'
  publicize_twitter_user: AgileAragon
  _oembed_time_63669ef5bc4282177293b63eb3768b07: '1464889301'
  _oembed_time_54c32c454c9490d61904885ddb51b144: '1464889309'
  _oembed_ad1388a8bd0777c38656d2382c02fcc0: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:328px">     <div style="max-height:288px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_ad1388a8bd0777c38656d2382c02fcc0: '1464889328'
  _oembed_ef4005900e62c7ecdc9e68e9747da675: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
    .mu_clearfix:after { visibility: hidden; display: block; font-size: 0; content:
    " "; clear: both; height: 0; }* html #meetup_oembed .mu_clearfix, *:first-child+html
    #meetup_oembed .mu_clearfix { zoom: 1; }#meetup_oembed { background:#eee;border:1px
    solid #ccc;padding:10px;-moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;margin:0;
    font-family: ''Helvetica Neue'', Helvetica, Arial, sans-serif; font-size: 12px;
    }#meetup_oembed h3 { font-weight:normal; margin:0 0 10px; padding:0; line-height:26px;
    font-family:Georgia,Palatino,serif; font-size:24px }#meetup_oembed p { margin:
    0 0 10px; padding:0; line-height:16px; }#meetup_oembed img { border:none; margin:0;
    padding:0; }#meetup_oembed a, #meetup_oembed a:visited, #meetup_oembed a:link
    { color: #1B76B3; text-decoration: none; cursor: hand; cursor: pointer; }#meetup_oembed
    a:hover { color: #1B76B3; text-decoration: underline; }#meetup_oembed a.mu_button
    { font-size:14px; -moz-border-radius:3px;-webkit-border-radius:3px;border-radius:3px;border:2px
    solid #A7241D;color:white!important;text-decoration:none;background-color: #CA3E47;
    background-image: -moz-linear-gradient(top, #ca3e47, #a8252e); background-image:
    -webkit-gradient(linear, left bottom, left top, color-stop(0, #a8252e), color-stop(1,
    #ca3e47));disvplay:inline-block;padding:5px 10px; }#meetup_oembed a.mu_button:hover
    { color: #fff!important; text-decoration: none; }#meetup_oembed .photo { width:50px;
    height:50px; overflow:hidden;background:#ccc;float:left;margin:0 5px 0 0;text-align:center;padding:1px;
    }#meetup_oembed .photo img { height:50px }#meetup_oembed .number { font-size:18px;
    }#meetup_oembed .thing { text-transform: uppercase; color: #555; }</style><div
    id="meetup_oembed" style="height:540px">     <div style="max-height:500px;overflow:hidden">          <h3>#FridayDojo:
    Kata Gilded Rose (segunda parte)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    Jun 10, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">4 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">En el anterior dojo
    aprendimos a cubrir nuestro código legacy con tests con la Kata Gilded Rose.Ahora
    que tenemos la red de seguridad que nos dan los tests automáticos, podemos empezar
    a refactorizar sin miedo, pero ¿por dónde empezamos?, ¿cómo lo hacemos, ¿a dónde
    llegaremos?No te preocupes si no viniste a la anterior sesión porque hemos prepara...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231598524/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_ef4005900e62c7ecdc9e68e9747da675: '1464918784'
author:  francho
---
En el anterior dojo aprendimos a cubrir nuestro código legacy con tests
con la [Kata Gilded
Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata). 

Ahora que tenemos la red de seguridad que nos dan los tests automáticos,
podemos empezar a refactorizar sin miedo, pero ¿por dónde empezamos?,
¿cómo lo hacemos, ¿a dónde llegaremos?

No te preocupes si no viniste a la anterior sesión porque hemos
preparado los tests en Python, Rub, Java y C\#. 

¿Te vienes?

Fecha y hora: **Viernes 27 de Mayo a las 18:30**

Lugar: **ETOPIA Centro de Arte y Tecnología (Avenida Ciudad de Soria,
8)**

Material: 

• Descarga [el
código](https://github.com/emilybache/GildedRose-Refactoring-Kata) en el
lenguaje en el que quieras hacer la kata si quieres trabajar con tu
portátil, si no tienes, no pasa nada, trabajaremos en parejas.  

• Conviene que te leas las la [descripción de la
kata ](https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/master/GildedRoseRequirements.txt)antes
de venir ([Aquí](https://github.com/francho/kata-betabeers) en español
gracias a [@francholab](https://twitter.com/francholab)).

![]({{site.baseurl}}/img/posts/rFmnfu2.gif)

http://www.meetup.com/agilearagon/events/231598524/

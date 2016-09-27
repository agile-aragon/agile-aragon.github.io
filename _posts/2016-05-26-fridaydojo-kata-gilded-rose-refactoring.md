---
layout: post
title: "#FridayDojo: Kata Gilded Rose (refactoring)"
date: 2016-05-26 09:15:28.000000000 +02:00
type: post
published: true
status: publish
categories:
- General
tags: []
meta:
  _oembed_65d2e83b5356c1331f190f04e7b2d57d: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_077a6792116280ab37da5b9f13816f97: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_5716da9278bce03b0ea0c9532dc0bd2d: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_5716da9278bce03b0ea0c9532dc0bd2d: '1464246930'
  _publicize_job_id: '23194059017'
  _publicize_done_external: a:1:{s:7:"twitter";a:1:{i:6161812;s:57:"https://twitter.com/AgileAragon/status/735731084952895490";}}
  _publicize_done_6191518: '1'
  _wpas_done_6161812: '1'
  publicize_twitter_user: AgileAragon
  _oembed_1ada836a139b579bea15e1f2ae260d46: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_1ada836a139b579bea15e1f2ae260d46: '1464246936'
  _oembed_time_65d2e83b5356c1331f190f04e7b2d57d: '1464246936'
  _oembed_time_077a6792116280ab37da5b9f13816f97: '1464246940'
  _oembed_7b9d63eb35d252ad20b9024033ad53c0: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">2 agilistas
    Attending</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div><div class="photo"><img src="http://photos1.meetupstatic.com/photos/member/9/6/5/c/thumb_164318492.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_7b9d63eb35d252ad20b9024033ad53c0: '1464248759'
  _oembed_b1adcd6f46e5067f0692aede89068ab1: '<div class="embed-meetup"><style type="text/css">#meetup_oembed
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
    Kata Gilded Rose (refactoring)</h3>          <p style="margin:5px 0;font-size:16px">Friday,
    May 27, 2016,  6:30 PM</p>          <p style="margin: 0 0 5px;"><span style="font-size:14px">Sala
    Hispalinux</span><br /><span style="font-size:12px;">C/ San Blas, 104 Zaragoza,
    ES</span></p>          <span style="color:#4F8A10;font-size:16px;">7 agilistas
    Went</span>           <div style="margin:5px 0 10px" class="mu_clearfix">               <div
    class="photo"><img src="http://photos4.meetupstatic.com/photos/member/1/6/a/7/thumb_251345799.jpeg"
    /></div><div class="photo"><img src="http://photos2.meetupstatic.com/photos/member/7/9/0/3/thumb_251190979.jpeg"
    /></div>          </div>          <p style="line-height:16px">Aprenderemos a meter
    mano a código legacy con la Kata Gilded Rose.¿Te vienes?Fecha y hora: Viernes
    27 de Mayo a las 18:30Lugar: Local de Hispalinux (Calle San Blas 104)Material:• Descarga
    el código en el lenguaje en el que quieras hacer la kata. Comprueba que puedes
    ejecutar los tests y que están en rojo (sólo hay uno).• Conviene que te leas...</p>     </div>     <p
    style="margin:10px 0 0;"><a href="http://www.meetup.com/agilearagon/events/231413322/"
    target="_blank" class="mu_button"><strong>Check out this Meetup &rarr;</strong></a></p></div></div>'
  _oembed_time_b1adcd6f46e5067f0692aede89068ab1: '1464677685'
author:  francho
---
Aprenderemos a meter mano a código legacy con la [Kata Gilded
Rose](https://github.com/emilybache/GildedRose-Refactoring-Kata). 

¿Te vienes?

Fecha y hora: **Viernes 27 de Mayo a las 18:30**

Lugar: **Local de Hispalinux (Calle San Blas 104)**

Material: 

• Descarga [el
código](https://github.com/emilybache/GildedRose-Refactoring-Kata) en el
lenguaje en el que quieras hacer la kata. Comprueba que puedes ejecutar
los tests y que están en rojo (sólo hay uno).  

• Conviene que te leas las la [descripción de la
kata ](https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/master/GildedRoseRequirements.txt)antes
de venir. 

![]({{site.baseurl}}/img/posts/giphy.gif)

http://www.meetup.com/agilearagon/events/231413322/

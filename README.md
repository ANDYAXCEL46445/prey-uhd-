<!DOCTYPE html>
<html lang="es">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
<link rel="stylesheet" href="https://player.gnulahd.nu/player/main.css?v=1727807828" media="all">
<link href="https://fonts.googleapis.com/css?family=Noto+Sans+HK:400,700&display=swap" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js?v=1.2.4"></script>
<script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js?v=1.2.4"></script>
<script src="https://www4.hentaila.com/assets/js/typewatch.js?v=1.2.4"></script>

</head>
<body id="hentai" class="home">

<div id="aa-wp">

<div class="bd cont">


<div class="columns">
<main>
<em>opción 2, latino, hd-r</em><section class="section player">
<div class="video_options">
<ul class="video_options-list aa-tbs" data-tbs="aa-video" id="episode-options">
<li><span data-id="0" title="filemoon.sx" class="on"><i class="fa fa-play"></i> Opcion 1</span></li>
<li><span data-id="1" title="listeamed.net" ><i class="fa fa-play"></i> Opcion 2</span></li>
<li><span data-id="2" title="voe.sx" ><i class="fa fa-play"></i> Opcion 3</span></li>
<li><span data-id="3" title="waaw.to" ><i class="fa fa-play"></i> Opcion 4</span></li>
<li><span class="btn btn-download aa-mdl" data-mdl="mdl-download"><i style="display:inline-block;" class="fa-download"></i> Descargar </span></li>
</ul>
</div>
<div id="aa-video">
<div id="video-1" class="aa-tb anm-a on">
<div class="video" id="repro"></div>
</div>
</div>
</section>
<script>
var videos = [["filemoon.sx","https://filemoon.sx/e/et2hv34ue0fl"],["listeamed.net","https://listeamed.net/e/mMq75L8Jq195XPB"],["voe.sx","https://voe.sx/e/zufh6ase7lnu"],["waaw.to","https://waaw.to/e/fUaqzRSv3MzR"]]
</script>
<div id="mdl-download" class="mdl">
<div class="mdl-cn anm-b">
<div class="mdl-hd">
<button class="btn lnk mdl-close aa-mdl" type="button" data-mdl="mdl-download"><i class="fa-times"></i></button>
</div>
<div class="mdl-bd">
<div class="download-links">
<table>
<thead>
</thead>
<tbody>

<tr>
<td><img src="uploads/Captura de pantalla 2024-06-02 a la(s) 3.58.45 p. m..png" style="width: 120px;height: 34px;"></td>
<td>latino</td>
<td><span>hd-r</span></td>
<td><a rel="nofollow" target="_blank" href="https://megaup.net/98a5b4e7efc5642ab94fb5ef81c51dbc/RGVhZHBvb2wgJiBXb2x2ZXJpbmUgKDIwMjQp.LAT.mp4" class="btn-download2 sm rnd">Descargar</a></td>
</tr>
<tr>
<td><img src="uploads/Captura de pantalla 2024-06-02 a la(s) 3.58.56 p. m..png" style="width: 120px;height: 34px;"></td>
<td>latino</td>
<td><span>hd-r</span></td>
<td><a rel="nofollow" target="_blank" href="https://gofile.io/d/SLYYuY" class="btn-download2 sm rnd">Descargar</a></td>
</tr>
<tr>
<td><img src="uploads/Captura de pantalla 2024-06-02 a la(s) 3.59.00 p. m..png" style="width: 120px;height: 34px;"></td>
<td>latino</td>
<td><span>hd-r</span></td>
<td><a rel="nofollow" target="_blank" href="http://gamovideo.com/h9il74hz9lsv" class="btn-download2 sm rnd">Descargar</a></td>
</tr>
<tr>
<td><img src="uploads/Captura de pantalla 2024-06-02 a la(s) 3.59.15 p. m..png" style="width: 120px;height: 34px;"></td>
<td>latino</td>
<td><span>hd-r</span></td>
<td><a rel="nofollow" target="_blank" href="https://1fichier.com/?bm00ocpq36blqml7zscn" class="btn-download2 sm rnd">Descargar</a></td>
</tr>
<tr>
<td><img src="uploads/Captura de pantalla 2024-06-02 a la(s) 3.59.20 p. m..png" style="width: 120px;height: 34px;"></td>
<td>latino</td>
<td><span>hd-r</span></td>
<td><a rel="nofollow" target="_blank" href="https://powvideo.org/2s2prhr199jb" class="btn-download2 sm rnd">Descargar</a></td>
</tr>

</tbody>
</table>
</div>
</div>
</div>
<div class="mdl-ovr aa-mdl" data-mdl="mdl-download"></div>
</div>

</main>

</div>
</div>


</div>




<script>
jQuery(document).ready(function($) {

 renderVideo = function(id) {
        $('#repro').html('<iframe width="560" height="315" frameborder="0" src="' + videos[id][1] + '" scrolling="no" allowfullscreen></iframe>');
    };

 $(document).on('click', '#episode-options li span', function(e) {
        e.preventDefault();
        $('#episode-options li span').removeClass('on');
        $(this).addClass('on');
        var currentId = $(this).data('id');
        var video = videos[currentId];
		
        renderVideo(currentId);       
        return false;
    });
    $(document).on('click', '.aa-cnt.aa-act.sub-menu li a', function(e) {
        e.preventDefault();
        var filter = $(this).data('filter');
        $('.aa-cnt.sub-menu li a').parent().removeClass('on');
        $(this).parent().addClass('on');
        var url = new URL(window.location.href);
        url.searchParams.set('filter', filter);
        var newUrl = url.href;
        window.location = newUrl;
    });



$('.aa-drp').each(function() {
        var $AADrpdwn = $(this);
        $('.aa-lnk', $AADrpdwn).click(function(e) {
            e.preventDefault();
            $AADrpdDv = $('.aa-cnt', $AADrpdwn);
            $AADrpdDv.parent('.aa-drp').toggleClass('on');
            $('.aa-cnt').not($AADrpdDv).parent('.aa-drp').removeClass('on');
            return false;
        });
    });
	
    $('.aa-tgl').on('click', function() {
        var shwhdd = $(this).attr('data-tgl');
        $('#' + shwhdd).toggleClass('on');
        $(this).toggleClass('on');
    });
	
    $('.aa-tgle').on('click', function() {
        var shwhdde = $(this).attr('data-tgle');
        $('#' + shwhdde).toggleClass('on');
        $(this).toggleClass('on');
    });
	
    $('.aa-tglo').on('click', function() {
        var shwhddo = $(this).attr('data-tglo');
        $('#' + shwhddo).toggleClass('on');
        $(this).toggleClass('on');
    });
	
    $(document).on('click', function(e) {
        if ($(e.target).closest('.aa-cnt').length === 0) {
            $('.aa-cnt').parent('.aa-drp').removeClass('on');
        }
    });
	
    $('.aa-tbs a').click(function(e) {
        e.preventDefault();
        var $this = $(this),
            tabgroup = '#' + $this.parents('.aa-tbs').data('tbs'),
            others = $this.closest('li').siblings().children('a'),
            target = $this.attr('href');
        others.removeClass('on');
        $this.addClass('on');
        $(tabgroup).children().removeClass('on');
        $(target).addClass('on');
    });
	
    $('body').on('click', '.aa-mdl', function() {
        var shwhddb = $(this).attr('data-mdl');
        $('#' + shwhddb).toggleClass('on');
        $('body').toggleClass('mdl-on');
        $(this).toggleClass('on');
        if (shwhddb == 'mdl-alert') {
            $('#' + shwhddb).remove();
        }
    });
	
    $(document).keyup(function(e) {
        if (e.keyCode === 27) {
            $('body').removeClass('mdl-on');
            $('.mdl').removeClass('on');
        }
    });
	
	renderVideo(0);
	
	});
</script>


 
<style>
em {
   color: #d1cbc1;  
   font: 14px century gothic, verdana, sans-serif;   
   font-style: italic !important;
}

.download-links tbody {
overflow: scroll;
max-height: 300px;		
}
.btn-download {
font-style: italic;
font-weight: bold;	
}

.download-links tbody, .download-links tr, .download-links td:last-child {
display: inline-block;		
}

.btn.mdl-close, .btn.mdl-close:hover { 
background-color: #c45908;
}
.download-links tbody {
overflow: auto;	
}


/* ===== Scrollbar CSS ===== */
  /* Firefox */
  * {
    scrollbar-width: thin;
    scrollbar-color: #c45908 #382f2a;
  }

  /* Chrome, Edge, and Safari */
  *::-webkit-scrollbar {
    width: 16px;
  }

  *::-webkit-scrollbar-track {
    background: #ffffff;
  }

  *::-webkit-scrollbar-thumb {
    background-color: #8f54a0;
    border-radius: 10px;
    border: 3px solid #ffffff;
  }
  
  .video_options {
	  background: #131313;
  }
  
  .video_options li span.on {
	border-top-color: #c45908;  
  }
  
  .video_options li span i {
	color: #c45908;  
  }

.section {
	max-height:435px;
}

    .download-links tr { 
	margin-bottom: 0;	
    padding: 1px !important;	
    width: 100%;
	
	display: flex;
    justify-content: center;
    align-items: center;
	
	
	}
	
	.btn-download2 {
	padding: 1px;	
	font-size: 12px;
	width: 100px;
	}
	
	.download-links tbody {
	max-height:600px;	
	width: 100%;
	}
	
	.video_options li span {
	padding: .2rem 1rem;
    }
	
	.rnd {
    border-radius: 10px;
    }
	
	a:hover {
	color:#fff;	
	box-shadow: 0 3px 3px 0 rgb(244 249 255 / 15%), 0 3px 1px -2px rgb(243 243 243 / 20%), 0 1px 5px 0 rgb(234 234 235 / 15%);
	background: #de660b;
	}
	
	.mdl-hd {
	padding: 0;
	border-bottom: 0;
	}
	
	.mdl-hd .mdl-title {	
    font-size: 1.1rem;
    line-height: 0.5rem;	
		
	}
	
	.mdl-bd {
	padding: 0;	
	}
	
	.download-links tr {
	background: #000;	
	}
	
	.download-links td, .download-links th {
    padding: .3rem;
}
  
  .video_options-list li {
   z-index: 999999999999999;
   position:relative;
  }
	
	


</style>



</body>
</html>

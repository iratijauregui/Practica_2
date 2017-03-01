$(document).ready(function(){ 

		$('.imageGrande').click(function(){   
		
		if ($(this).find('img').data('num')=='1'){		
			//window.alert("aa");
			$('#imagenPrincipal').attr("src","cuadro_1_large.jpg");

			/* $(".imagenPequeña").css("display", "block"); 
			$(".imagenPequeña3").css("display", "none"); 
			$(".imagenPequeña2").css("display", "none");  */
			$("#escribir").text($(this).find('img').data('descripcion'));
			$(".producto").attr("value",($(this).find('img').attr("value")));
			
		    $('.pulsaImagen').first().attr('src','cuadro_11_thumb.png');
			$('.pulsaImagen').first().next().attr('src','cuadro_12_thumb.png');
			$('.pulsaImagen').first().next().next().attr('src','cuadro_13_thumb.png');

						//window.alert($(".producto").prop('value'));



		}else if($(this).find('img').data('num')=='2'){	
		//window.alert("bb");
			$('#imagenPrincipal').attr("src","cuadro_2_large.jpg");
/* 			$(".imagenPequeña2").css("display", "block"); 
			$(".imagenPequeña").css("display", "none"); 
			$(".imagenPequeña3").css("display", "none");  */
			$("#escribir").text($(this).find('img').data('descripcion'));
			$(".producto").attr("value",($(this).find('img').attr("value")));
			//window.alert($(".producto").prop('value'));
			
			$('.pulsaImagen').first().attr('src','cuadro_21_thumb.png');
			$('.pulsaImagen').first().next().attr('src','cuadro_22_thumb.png');
			$('.pulsaImagen').first().next().next().attr('src','cuadro_23_thumb.png');


		}else if($(this).find('img').data('num')=='3'){	
		//window.alert("bb");
			$('#imagenPrincipal').attr("src","cuadro_3_large.jpg");
/* 			$(".imagenPequeña3").css("display", "block"); 
			$(".imagenPequeña").css("display", "none"); 
			$(".imagenPequeña2").css("display", "none");  */
			$("#escribir").text($(this).find('img').data('descripcion'));
			$(".producto").attr("value",($(this).find('img').attr("value")));
			//window.alert($(".producto").prop('value'));
					
			  $('.pulsaImagen').first().attr('src','cuadro_31_thumb.png');
			$('.pulsaImagen').first().next().attr('src','cuadro_32_thumb.png');
			$('.pulsaImagen').first().next().next().attr('src','cuadro_33_thumb.png');
		}
		
	});

	$(".menu").find("li").click(function(activar){  
        var a = activar.target.id;  
        //activamos elemento de menu  
        $(".menu").find("li.active").removeClass("active");  
        $(".menu #"+a).addClass("active");  
        //mostramos la seleccionada  
        $(".content").css("display", "none");  
        $("."+a).fadeIn();  
    });  
	
	/* $('#imgGrande').find('images').click(function(){
		$('#largeImage').attr('src',$(this).attr('src').replace($(this).attr('src'),$('#imgGrande').attr('src')));
	 */
	
	//Otras imagenes de prpoducto
	$('.pulsaImagen').click(function(){   
	
/* 	$('#imagenPrincipal').fadeOut();
	
	$('#imagenPrincipal').fadeIn();
 */	
	$('#imagenPrincipal').css("display", "none");

		$('#imagenPrincipal').attr("src",$(this).attr("src"));

	$('#imagenPrincipal').fadeIn(500);

	});
	
	
	
	
	
	//Precio de productos
	
	$('.producto').on('keyup','.cantidad',function(){
		var precio = $('.producto').attr('value');
		var cantidad = +$(this).val();
		$('#total').text(precio * cantidad);
	});
	
	//Cuadro resumen y precio total
		//1 producto
		$('.producto').on('keyup','.cantidad',function(){
			//window.alert($('.producto').attr('value'));
			var precio = $('.producto').attr('value');
			var cantidad = +$(this).val();
			var preciototal = precio*cantidad;




			if (precio==50){
			$('#cantidad1').text(cantidad);
			$('#precioProducto1').text(precio*cantidad);
			$(".cuadro1precio").prop("value",precio*cantidad);
			

			}else if (precio==75){
				$('#cantidad2').text(cantidad);
			$('#precioProducto2').text(precio*cantidad);
			$(".cuadro2precio").prop("value",precio*cantidad);

			}else if (precio==60){
				$('#cantidad3').text(cantidad);
			$('#precioProducto3').text(precio*cantidad);
			$(".cuadro3precio").prop("value",precio*cantidad);

			}
			

			var preciofinal = $(".cuadro1precio").val() + $(".cuadro2precio").val()+ $(".cuadro3precio").val();

			$('#precioTotal').text( preciofinal);

		});
		
		
		
	/* 	//Coste total
		$('.producto').on('keyup','.cantidad',function(){
			var precio = +$(this).closest('.producto').data('precio');
			var cantidad = +$(this).val();
			var preciototal = precio*cantidad;
			$('#precioTotal').text(preciototal);
		}); */

}); 
	
	
	
	/*	//Seleccionar foto principal
	
	var foto = new Array();
				foto[0] = "cuadro1.jpg";
				foto[1] = "cuadro2.jpg";
				foto[2] = "cuadro3.jpg";
				
	var fotoprincipal=0;
	var fotocentro=0;
	
	$('button').on('click',function seleccion(){
		var posicion = $(this).id;
		var objeto=document.getElementById("imagen0");
		var completa=document.getElementById("imagencompleta");
		var x=fotocentro + posicion;
		fotoprincipal=x;
		objeto.src=foto[fotoprincipal];
		completa.src = foto[fotoprincipal];
	}*/	
	
	
	
		
	
	

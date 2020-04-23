$(function(){

        var $header = $('<div class="label" style="position:absolute; top:0px; left:0px; background-color:rgba(0,0,0,0.7); padding:10px; color:#fff;"><h3>HEADER</h3></div>'),
            $aside = $('<div class="label" style="position:absolute; top:0px; left:0px; background-color:rgba(0,0,0,0.7); padding:10px; color:#fff;"><h3>ASIDE</h3></div>'),
            $content = $('<div class="label" style="position:absolute; top:0px; left:0px; background-color:rgba(0,0,0,0.7); padding:10px; color:#fff;"><h3>CONTENT</h3></div>'),
            $footer = $('<div class="label" style="position:absolute; top:0px; left:0px; background-color:rgba(0,0,0,0.7); padding:10px; color:#fff;"><h3>FOOTER</h3></div>');


        $('#wireframe .container').mouseenter(function(){
                var $el = $(this);

                $el.css( { border : "1px dashed #555", padding : "0px 9px" })

                if($el.parent().is('header')) {
                        $el.append($header);
                }

                if($el.parent().is('aside')) {
                        $el.append($aside);
                }

                if($el.parent().is('section')) {
                        $el.append($content);
                }

                if($el.parent().is('footer')) {
                        $el.append($footer);
                }


        });


        $('#wireframe .container').mouseleave(function(){
                $('.label').remove();
                $(this).css( { border : "0px dashed #555", padding : "0px 10px" })

        });




});

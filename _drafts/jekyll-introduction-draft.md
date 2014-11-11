---
layout: post
category : lessons
tagline: "Supporting tagline"
tags : [intro, beginner, jekyll, tutorial]
---
{% include JB/setup %}


This is an example of a draft. Read more here: [http://jekyllrb.com/docs/drafts/](http://jekyllrb.com/docs/drafts/)


<script type="text/javascript">
    $(document).ready(function(){       
        var scroll_start = 0;
        var startchange = $('#startchange');
        var offset = startchange.offset();
        if (startchange.length){
            $(document).scroll(function() { 
                scroll_start = $(this).scrollTop();
                if(scroll_start > offset.top) {
                    $(".navbar-default").css('background', '#ffffff');
                    $('.navbar-default').css('border-bottom', '#000000 solid 1px');
                    $(".nav-pills>li>a").css('background', 'transparent');
                    $(".nav-pills>li>a").css('color', '#5cb8e6');
                    $(".navbar-brand").css('display', 'block');
                    

                } else {
                    $('.navbar-default').css('background-color', 'transparent');
                    $('.navbar-default').css('border-color', '#5cb8e6');
                     $(".navbar-brand").css('display', 'none');


                }

            });
        };
        
    });
</script>
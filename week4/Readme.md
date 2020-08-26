# Bootstrap and JQuery 
Is a very powerful, lightweigth Javascript based library that provides a number of different components. 

## Bootstrap JQuery Example 

### This is an example of JQuery sintax
<script>
    $(document).ready(function(){
        $('[data-toggle="tooltip"]'.tooltip();
    });
</script>

### JQuery slectors 

- Any Html element e.g., "p", "button" etc.
- Using an #id, e.g., "#myCarousel"
- class, e.g, ".btn", ".btn.btn-default"
- Attribute, e.g, "[href]", "[data-toggle="tooltip"]"
- Current element: $(this).

### JQuery events 

- User's interactions on a web page causing DOM events: 
- JQuery event methods: e.g, ready(), click()...  

# Example Carousel 

- Javascript base control:  
    - $('Carousel').carousel();
    - e.g 
        $('.carousel').carousel({interval:2000});

- Other controls: 
    - .carousel('cycle'): cycle items left to right
    - .carousel('pause'): stops the carousel
    - .carousel(number): cucles the carousel to a particular frame number specified. 
    - .carousel('prev'): previous item
    - .carousel('next'):next item.
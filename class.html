<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="demo.js"></script>
<script>
// open popup prompt for ask name of user
var name = prompt("Enter your name:", "Guest");
// default name is 'Guest'
if (!name || name === ' ') {
  name = "Guest";
}
// strip tags
name = name.replace(/(<([^>]+)>)/ig,"");
// display name on page
$("#user-name").html("User: <strong>" + name + "</strong>");
var chat =  new Chat();
$(function() {
   chat.getState();
   /* define function when key presses */
   $("#posttext").keydown(function(event) {
       var key = event.which;
       /* if key including return. */
       if (key >= 33) {
           var maxLength = $(this).attr("maxlength");
           var length = this.value.length;
           /* define limit of new content */
           if (length >= maxLength) {
               event.preventDefault();
           }
       }
   });
   /* define function when key release */
   $('#posttext').keyup(function(e) {
      if (e.keyCode == 13) {
            var text = $(this).val();
            var maxLength = $(this).attr("maxlength");
            var length = text.length;
            // send
            if (length <= maxLength + 1) {
              chat.send(text, name);
              $(this).val("");
            } else {
              $(this).val(text.substring(0, maxLength));
            }
      }
   });
});
</script>

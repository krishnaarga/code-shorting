# Code Shorting
Long Code to Short Code

# 1. Submit larg FORM data with simple code
$( "form" ).on( "submit", function( event ) {
  console.log( $( this ).serializeArray() );
  event.preventDefault();
});

# 2. Add --mysqli_real_escape_string-- in whole variable in one time
foreach ($_POST as $key=>$value) { $_POST[$key] = mysqli_real_escape_string($connection, $value); }

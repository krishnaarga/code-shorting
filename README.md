# code-shorting
Long Code to Short Code

# Submit larg FORM data with simple code
$( "form" ).on( "submit", function( event ) {
  console.log( $( this ).serializeArray() );
  event.preventDefault();
});

# Add --mysqli_real_escape_string-- in whole variable in one time
foreach ($_POST as $key=>$value) { $_POST[$key] = mysqli_real_escape_string($connection, $value); }

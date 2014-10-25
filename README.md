Bootstrap Disable Responsive

Used

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    
    <link href="css/disable-responsive.css" rel="stylesheet">
  </head>
  
  Example
  
  <html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap -->
    <?php $responsive = true; ?>
    
    <link href="css/bootstrap.min.css" rel="stylesheet">
    
    <?php if($responsive == false){ echo '<link href="css/disable-responsive.css" rel="stylesheet">'; }  ?>

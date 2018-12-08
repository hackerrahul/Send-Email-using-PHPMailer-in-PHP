# Send Email using PHPMailer in PHPMailer
Open **`sendemail.php`** and edit these lines.
``` php
 //Server settings
    $mail->SMTPDebug = 0;                                     // Enable verbose debug output
    $mail->isSMTP();                                         // Set mailer to use SMTP
    $mail->Host = 'YOUR_HOST_HERE';                       	// Specify main and backup SMTP servers
    $mail->SMTPAuth = true;                                // Enable SMTP authentication
    $mail->Username = 'YOUR_HOST_HERE';             // SMTP username
    $mail->Password = 'YOUR_HOST_HERE';                              // SMTP password
    $mail->SMTPSecure = 'tls';                          // Enable TLS encryption, `ssl` also accepted
    $mail->Port = 587;                                 // TCP port to connect to
    //Recipients
    $mail->setFrom('YOUR_HOST_HERE', 'YOUR_NAME');	 //SET "FROM" EMAIL AND NAME. 
```    
Just Replace **`YOUR_HOST_HERE`**, **`YOUR_HOST_HERE`**, **`YOUR_HOST_HERE`**, **`YOUR_HOST_HERE`** and **`YOUR_NAME`** from these lines.
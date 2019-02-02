+++
title = 'Connect'
+++

# Connect With Us!
By joining our network you will be able to use the Internet for free and
also help other students to connect to our network.
Please fill in the form below and we will help you out with connecting to
LTU Mesh!

<!-- The form is just a dummy without any actual real API call -->
<form action="#does_not_exist_yet" method="post">
<!-- Each set of fields are contained in a fieldset-tag (just one
		currently) -->
<fieldset>
<!-- fieldset legend -->
<legend>Connect</legend>

<label for="name">Your name:</label><br>
<input id="name" type="text" name="name"><br><br>

<label for="telephone">Telephone number:</label><br>
<input id="telephone" type="text" name="telephone"><br><br>

<label for="email">E-mail:</label><br>
<input id="email" type="text" name="email"><br><br>

<label for="address">Address:</label><br>
<!-- Textarea with 60 character width and 5 row height -->
<textarea id="address" name="address" cols="60" rows="5"></textarea><br><br>

<input type="submit" name="connect" value="Connect me!">
<!-- The reset type clears the whole form -->
<input type="reset" value="Reset">
</fieldset>
</form>

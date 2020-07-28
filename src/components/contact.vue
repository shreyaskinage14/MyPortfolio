<template>
	<section>
	<div id="contactt">
		<div class="info">
			<h2>Contact Info</h2>
			<ul class="deta">
				<li>
					<span><i class="fa fa-map-o"></i></span>
					<span>G4, Blg No.9,<br>
					Sawant Park,<br>
					Ambernath(E)-421501</span>
				</li>
				<li>	
					<span><i class="fa fa-envelope-square"></i></span>
					<span>shreyaskinage14@gmail.com</span>
				</li>
				<li>
					<span><i class="fa fa-phone"></i></span>
					<span>838-0944-344</span>
				</li>
			</ul>
			<ul class="sci">
				<a href="https://www.facebook.com/shreyas.kinage/" target="_blank" class="fa fa-facebook"></a>
				<a href="https://www.twitter.com/shreyaskinage14/" target="_blank" class="fa fa-twitter"></a>
				<a href="https://www.instagram.com/iamshreyaskinage/" target="_blank" class="fa fa-instagram"></a>
				<a href="https://github.com/shreyaskinage14/" target="_blank" class="fa fa-github"></a>
				<a href="https://www.linkedin.com/in/shreyaskinage14/" target="_blank" class="fa fa-linkedin"></a>
			</ul>
		</div>
		<div class="conform">
			<h2>Send a message :)</h2>
			<div class="forbox">
			<div class="inputbox w50">
				<input type="text" name="fname" required>
				<span>First Name</span>
			</div>
			<div class="inputbox w50">
				<input type="text" name="lname" required>
				<span>Last Name</span>
			</div>
			<div class="inputbox w50">
				<input type="text" name="ename" required>
				<span>Email Address</span>
			</div>
			<div class="inputbox w50">
				<input type="text" name="pname" required>
				<span>Mobile Number</span>
			</div>
			<div class="inputbox w100">
				<textarea name="" required></textarea>
				<span>Write your message here...</span>
			</div>
			<div class="inputbox w100	">
				<input type="submit" value="Send" onclick="alert('Thank You!')">
			</div>
			</div>
		</div>
	</div>
	</section>
</template>
<script>
	export default{
		name:'Contact'
	}
</script>
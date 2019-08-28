<template>
  <div class="hello">
      <div class="container">
		<h1 class="">Create An Account on the Steem Blockchain</h1>
		<form action="" class="was-validated">
			<div class="form-group">
				<label for="uname">Username:</label>
				<input type="text" class="form-control" id="uname" placeholder="Enter username" name="uname" required>
				<div class="valid-feedback">Valid.</div>
				<div class="invalid-feedback">Please fill out this field.</div>
			</div>
			<div class="form-group">
				<label for="pwd">Recovery Email</label>
				<input type="email" class="form-control" id="email" placeholder="Enter Recovery Email" name="email" required>
				<div class="valid-feedback">Valid.</div>
				<div class="invalid-feedback">Please fill out this field.</div>
			</div>
			<div class="form-group">
                <label for="sel1">Select Payment Method:</label>
                <select class="form-control" id="sel1">
                    <option>LTC</option>
                    <option>USDT</option>
                    <option>TUSD</option>
                    <option>PayPal</option>
                </select>
            </div>
			<button type="submit" class="btn btn-primary">Validate Username And Proceed to Payment</button>
		</form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

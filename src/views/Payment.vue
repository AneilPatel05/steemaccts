<template>
  <div class="hello">
		<table class="table">
			<thead class="thead-dark">
				<tr>
					<th>Account Name</th>
					<th>Amount</th>
					<th>Payment Address</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>fyrsttest</td>
					<td>0.0146 LTC</td>
					<td>LTCsfhjgsjfghkpdjflds5fd4df225</td>
				</tr>
			</tbody>
		</table>
		<span>Please pay the Exact Amount to the specified Address within : 60 Min</span>
		<br>
		<span>Waiting for Payment ...</span>
		<br>
		<button  @click="confirmPayment()" class="btn btn-primary">I have paid</button>
  </div>
</template>

<script>
export default {
	name: 'Payment',
	methods:{
		confirmPayment(){
			this.$router.push('/details/1')
		}
	}
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

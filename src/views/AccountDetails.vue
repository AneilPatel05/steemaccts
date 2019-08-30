<template>
  <div class="hello">
		<table class="table">
			<thead class="thead-dark">
				<tr>
					<th>Type</th>
					<th>Private Key</th>
					<th>Public Key</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>Owner</td>
					<td>5kdfbdkfbjdbvjdvjdvnjzdvn</td>
					<td>STMbjdbfjbadjbdbvjobdvbjcbcj</td>
				</tr>
				<tr>
					<td>Active</td>
					<td>5kdfbdkfbjdbvjdvjdvnjzdvn</td>
					<td>STM5kdfbdkfbjdbvjdvjdvnjzdvn</td>
				</tr>
				<tr>
					<td>Posting</td>
					<td>5kdfbdkfbjdbvjdvjdvnjzdvn</td>
					<td>STM5kdfbdkfbjdbvjdvjdvnjzdvn</td>
				</tr>
				<tr>
					<td>Memo</td>
					<td>5kdfbdkfbjdbvjdvjdvnjzdvn</td>
					<td>STM5kdfbdkfbjdbvjdvjdvnjzdvn</td>
				</tr>
			</tbody>
		</table>
		<button @click="createAccount()" class="btn btn-primary">create Account</button>
  </div>
</template>

<script>
export default {
  name: 'AccountDetails',
  methods:{
	createAccount(){
		this.$router.push('/')
	}
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

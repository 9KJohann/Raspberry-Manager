<form action="">
	<div class="row">
		<div class="col"><span>IP-Zuweisung</span></div>
		<div class="col">
			<input type="radio" id="dhcp" name="ipAssignment" value="dhcp" />
			<label for="dhcp">dhcp</label>
			<input type="radio" id="static" name="ipAssignment" value="static" />
			<label for="static">static</label>
		</div>
	</div>
	<div class="row">
		<div class="col"><span>IPv4</span></div>
		<div class="col">
			<input type="text" />
		</div>
	</div>
</form>

<style>
	.row {
		display: flex;
	}
	.col {
		width: 50%;
	}
</style>

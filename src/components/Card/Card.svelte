<script>
	import Badge from '../Badge/Badge.svelte';
</script>

<div>
	<div class="card w-96 bg-base-100 shadow-xl cursor-pointer transform transition duration-300 hover:scale-[1.01]">
		<div class="card-body">
			<h2 class="card-title">Card title!</h2>
			<p>If a dog chews shoes whose shoes does he choose?</p>
			<div class="card-actions">
				<Badge type={'success'} text={'Done'} />
			</div>
		</div>
	</div>
</div>

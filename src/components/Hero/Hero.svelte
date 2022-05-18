<script>
	import CreateTodoModal from '../CreateTodoModal/CreateTodoModal.svelte';
</script>

<div class="text-center mb-10">
	<h1 class="font-extrabold text-transparent text-8xl bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600">TODO APP
	</h1>
</div>
<div class="text-center mb-24">
	<label for="test-modal" class="btn btn-primary modal-button">Create TODO</label>
</div>

<CreateTodoModal />

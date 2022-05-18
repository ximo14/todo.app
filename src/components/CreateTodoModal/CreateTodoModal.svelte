<script lang="ts">
</script>

<input type="checkbox" id="test-modal" class="modal-toggle" />
<div class="modal">
	<div class="modal-box">
		<h3 class="font-bold text-lg">
			Create a <span class="font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-600">TODO</span
			>card!
		</h3>
		<form action="">
			<div>
				<div>
					<p class="py-4">Please, fill all the following fields to create the TODO card!</p>
					<div class="space-y-3">
						<input type="text" placeholder="Title" class="input input-bordered w-full max-w-xs" />
						<textarea class="textarea textarea-bordered w-full h-32" placeholder="Description" />
						<div class="flex justify-center">
							<div class="btn-group">
								<button class="btn btn-active" data-key="todo">To do</button>
								<button class="btn" data-key="doing">Doing</button>
								<button class="btn" data-key="done">Done</button>
							</div>
						</div>
					</div>
				</div>
				<div class="modal-action">
					<button for="test-modal" type="submit" class="btn btn-success">Create</button>
					<label for="test-modal" class="btn btn-error">Cancel</label>
				</div>
			</div>
		</form>
	</div>
</div>

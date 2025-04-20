<script lang="ts">
	import type { PageData } from './$types.js';
	import * as Card from '$lib/components/ui/card/index.js';
	import ResetForm from './reset-form.svelte';

	export let data: PageData;
</script>

<Card.Root class="min-w-[500px] max-w-sm">
	<Card.Header class="min-h-[120px]">
		<Card.Title class="text-2xl">Reset Password</Card.Title>
		<Card.Description>Enter your email address</Card.Description>
	</Card.Header>
	<Card.Content>
		<ResetForm data={data.form} />
	</Card.Content>
</Card.Root>

<!--
SPDX-FileCopyrightText: 2025 Iverson Briones <ivercoder@proton.me>

SPDX-License-Identifier: AGPL-3.0-or-later
-->

<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<title>Prefectuary</title>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

{@render children()}

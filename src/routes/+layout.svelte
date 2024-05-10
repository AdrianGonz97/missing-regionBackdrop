<script lang="ts">
	import "../app.postcss";
	import { Modal, initializeStores } from "@skeletonlabs/skeleton";

	initializeStores();
</script>

<Modal regionBackdrop="!bg-black/[.24]" />
<slot />

<!-- 👇 (note the lack of `lang="ts"` attribute) -->
<script>
	// this import causes the app to break because of the `.js` extension
	import { foo } from "./foo.js";

	// however, using a `.ts` extension fixes it...
	// import { foo } from "./foo.ts";

	foo();
</script>

<h1>JS Component</h1>

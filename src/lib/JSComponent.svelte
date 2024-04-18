<script>
	// import causes the app to break because of the `.js` extension (note the lack of `lang="ts"` attribute)
	import { foo } from "./foo.js";
	// import { foo } from "./foo.ts";

	foo();
</script>

<h1>JS Component</h1>

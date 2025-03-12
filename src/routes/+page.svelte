<script lang="ts">
	import {masked} from '$lib';
</script>

<h1>Demo</h1>
<input type="text" use:masked={'###-###-###'} />
<input type="text" use:masked={'##.##.####'} />
<input type="text" use:masked={'AAA-###-aaa'} />
<input type="text" use:masked={'+1 (###) ###-####'} />
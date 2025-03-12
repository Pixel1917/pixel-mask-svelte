<script lang="ts">
	import {masked} from '../lib/index';
</script>

<h1>examples</h1>
<input type="text" use:masked={'###-###-###'} />
<input type="text" use:masked={'##.##.####'} />
<input type="text" use:masked={'AAA-###-aaa'} />
<input type="text" use:masked={'+1 (###) ###-####'}>
# Svelte mask library

Tiny (8.5kb) mask library. Supports svelte 4 and svelte 5;
Pretty easy to use;

### Installation
```bash
npm i pixel-mask-svelte
```

### Usage
```sveltehtml
<script lang="ts">
import {masked} from 'pixel-mask-svelte';
</script>

<input type="text" use:masked={'###-###-###'} />
<input type="text" use:masked={'##.##.####'} />
<input type="text" use:masked={'AAA-###-aaa'} />
<input type="text" use:masked={'+1 (###) ###-####'} />
```

### Patterns
<table>
    <thead>
        <tr>
            <th>Placeholder</th>
            <th>Format</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#</td>
            <td>Number (0-9)</td>
        </tr>
        <tr>
            <td>S</td>
            <td>Letter in any case (a-z,A-Z)</td>
        </tr>
        <tr>
            <td>A</td>
            <td>Letter in upper case</td>
        </tr>
        <tr>
            <td>a</td>
            <td>Letter in lower case</td>
        </tr>
        <tr>
            <td>X</td>
            <td>Any symbol</td>
        </tr>
        <tr>
            <td>!</td>
            <td>Escape character</td>
        </tr>
    </tbody>
</table>
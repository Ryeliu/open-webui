<script lang="ts">
        import { ICP_INFO } from '$lib/constants';
</script>

{#if ICP_INFO}
        <footer class="w-full text-center text-xs text-gray-500 dark:text-gray-400 py-4">
                <a href="https://beian.miit.gov.cn" target="_blank" rel="noopener">{ICP_INFO}</a>
        </footer>
{/if}


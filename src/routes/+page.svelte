<script lang="ts">
    import { Tool, VectorImage } from "@anfr/ui";
</script>

{#snippet logotype()}
    <VectorImage viewBox="0 0 16.82 2.43">
        <defs>
            <style>
                .cls-1 {
                    fill: #bfbdb6;
                }
            </style>
        </defs>
        <path class="cls-1" d="M15.53.16c-.08-.1-.19-.16-.32-.16H.4C.07,0-.12.37.08.64l1.22,1.63c.08.1.19.16.32.16h14.81c.33,0,.51-.37.32-.64l-1.22-1.63Z"/>
    </VectorImage>
{/snippet}

<Tool name="Nothing" {logotype} --accent-color="#BFBDB6">
    Hello!
</Tool>
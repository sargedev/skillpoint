<script>
    import {pdf_files} from "$lib/data/pdf";
</script>

<table>
    <tbody>
        {#each Object.entries(pdf_files) as [year, categories]}
            <tr><td>{year}</td></tr>
        {/each}
    </tbody>
</table>
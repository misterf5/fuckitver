<script>
  import SvelteMarkdown from "svelte-markdown";
  import markdown from "../../fuckitver.md";
</script>

<main>
  <div class="markdown">
    <SvelteMarkdown source={markdown} />
  </div>
</main>

<style>
  .markdown {
    margin-left: auto;
    margin-right: auto;
    width: 740px;
    padding: 15px;
    border-style: solid;
    border-color: black;
    border-left-width: 2px;
    border-right-width: 2px;
    border-top-width: 0px;
    border-bottom-width: 0px;
  }
</style>

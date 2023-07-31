<script>
  import { closeModal } from "svelte-modals";

  // provided by <Modals />
  export let isOpen;

  export let title;
  export let message;
</script>

{#if isOpen}
  <div role="dialog" class="modal">
    <div class="contents">
      <h2>Biz bilan bog'laning</h2>
      <p>+998 88 376-66-06</p>
      <div class="actions">
        <button class="btn" on:click={closeModal}>OK</button>
      </div>
    </div>
  </div>
{/if}

<style>
  .modal {
    position: fixed;
    top: 0;
    bottom: 0;
    right: 0;
    left: 0;
    display: flex;
    justify-content: center;
    align-items: center;

    /* allow click-through to backdrop */
    pointer-events: none;
    z-index: 99;
  }

  .contents {
    min-width: 240px;
    border-radius: 6px;
    width: 700px;
    padding: 30px;
    background: white;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    pointer-events: auto;
  }

  h2 {
    font-size: 24px;
  }

  p {
    margin-top: 16px;
  }

  .actions {
    margin-top: 32px;
    display: flex;
    justify-content: flex-end;
  }

  .actions button {
    padding: 10px 20px;
  }
</style>

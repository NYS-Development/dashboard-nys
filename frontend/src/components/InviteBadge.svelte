<div class="guild-badge" on:click={invite}>
  <div class="guild-icon-bg">
    <i class="fas fa-plus fa-2x guild-icon-fa"></i>
  </div>

  <div style="padding-left: 10px">
    <span class="guild-name">Invite to your server</span>
  </div>
</div>

<script>
    function invite() {
        window.location.href = `https://discord.com/oauth2/authorize?client_id=1366150181216714904&permissions=242934606928&integration_type=0&scope=bot+applications.commands`;
    }
</script>

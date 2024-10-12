<script>
  import { Alert } from 'flowbite-svelte';
  import { Input, Label, Helper, Button } from 'flowbite-svelte';
</script>

<h1>Welcome to Red Hat Halloween AI Assistant</h1>
<form>
  <div class="mb-6">
    <div>
      <Label for="player_name" class="mb-2">Your name</Label>
      <Input type="text" id="player_name" placeholder="Ichibod Crane" required />
    </div>
    </div>
    <Button type="submit">Submit</Button>
</form>

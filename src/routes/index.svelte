<script>
  import TodoItem from "$lib/todo-item.svelte";

  const title = "TODO임ㅋ";
</script>

<svelte:head><title>{title}</title></svelte:head>
<h1>{title}</h1>

<form action="" method="">
  <input
    type="text"
    name=""
    id=""
    aria-label="Add a todo"
    placeholder="+ tap to add todo"
  />
</form>

<TodoItem />

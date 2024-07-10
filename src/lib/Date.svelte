<script>
  // Create a new Date object
  const today = new Date();

  // Get the day, month, and year
  const day = today.getDate();
  const month = today.getMonth() + 1; // Months are zero-indexed
  const year = today.getFullYear();

  // Format the date as a string
  const formattedDate = `${month}/${day}/${year}`;
</script>

<span id="currentDate">{formattedDate}</span>

<style>
  #currentDate {
    display: flex;
    justify-content: flex-end;
    padding: 1rem;
    position: fixed;
    bottom: 0;
    right: 0;
    font-size: 10px;
  }
</style>

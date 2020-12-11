<script>
  import Agenda from "@nylas/components-agenda";
  const staticEvents = [
    {
      title: "Some event that I am manipulating outside of the context of Nylas",
      description: "Passed in from HTML!",
      participants: [],
      when: { end_time: 1600444800, object: "timespan", start_time: 1600438500 }
    },
    {
      title: "Some I got from elsewhere",
      description: "Passed in from HTML!",
      participants: [],
      when: { end_time: 1600449999, object: "timespan", start_time: 1600448500 }
    },
    {
      title: "A third event of the day",
      description: "Passed in from HTML!",
      participants: [],
      when: { end_time: 1600468500, object: "timespan", start_time: 1600458500 }
    }
  ];
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
</style>

<main>
	<h1>Nylas Agenda</h1>
  <nylas-agenda events={staticEvents}/>
</main>
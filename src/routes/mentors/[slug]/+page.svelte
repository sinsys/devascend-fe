<script lang="ts">
  /* TODO: Utilize a service to load. Interface as requisites arise later */
  const mentor = {
    name: 'Nicholas Hazel',
    skills: ['Some', 'Predetermined', 'Technical', 'Tags'],
    timezone: 'America/Los_Angeles',
    description: 'The quick brown fox jumped over the lazy dogs'
  }
  /* TODO: This must be run with a highly coordinated service, preferably prebuilt.
    Calendly comes to mind?
    Must lazy load availability as well, as I imagine APIs will be relatively slow
    on calendar-based coordination. Furthermore, it will likely be sourced to an external
    service and we do not want the coupling to break the page */
  const mentorAvailability = true
</script>

<h1>Individual Mentor</h1>

<h2>{ mentor.name }</h2>
<ul>
  {#each mentor.skills as skill}
    <li>{skill}</li>
  {/each}
</ul>
<img src="/nicholas-hazel.jpg" alt="{mentor.name}" width="150px" />
<!--Quizz-->
<script>
import Header from "$lib/Header.svelte"
</script>

<Header headingTitle = "Dog matching Quiz"/>

<h3>Start the quiz to be one step closer to finding your perfect canine</h3>

<div>
    <form action="dog.quiz">
        <label for= "fname">First Name</label>
        <input type="text" id ="fname" name ="firstname" placeholder="Your name">

        <label for="lname">Last Name</label>
        <input type="text" id ="lname" name = "lastname" placeholder="Your last name">
    </form>
</div>
<script setup>

</script>

<template>
  <section id='welcome'>
    <div class='benefits'>
        <h2>Complete This Program<br/>If You Want To</h2>

        <div>
            <p>• Follow a simple program with proven result.</p>
            <p>• Get fit, healthy, strong and absolutely shredded.</p>
            <p>• Learn more about gym, training and technique.</p>
        </div>

        <div>
            <h3>
                The Training Plan
            </h3>
            <p>
                Tis training plan follows a structure known as the
                <strong>Bro Split</strong>.
            </p>
            <h5><i>Push &rarr; Pull &rarr; Legs &rarr; Repeat</i> &#x27F3;</h5>
        </div>

        <div class='card challenge'>
            <h3>&#128293; Your Challenge</h3>
            <p>Complete all your workouts and track all your progress along the way...!!</p>
            <p>Do You Accept ...?</p>
            <button> Begin &rarr;</button>
        </div>
    </div>
  </section>
</template>

<style scoped>
    #welcome,
    .challenge,
    .benefits{
        display: flex;
        flex-direction: column;
    }

    #welcome {
        gap: 1.5rem;
    }

    .benefits {
        gap: 0.5rem;
    }

    .challenge {
        gap: 0.25rem;
    }
</style>

<template>
    <div class=" w-full flex flex-col items-center px-32 py-10 text-white gap-24">
        <div class="w-full flex flex-row h-32 justify-between ">
            <h1>Atelier</h1>
            <div>Menu</div>
        </div>

        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
        <h2 class=" py-24 text-xl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris et nisi luctus,
            sollicitudin purus quis, ultrices risus. Curabitur luctus ante quam, a efficitur libero sollicitudin et. Nulla
            aliquam lorem dolor. Nunc in velit lectus. Sed diam justo, lobortis vitae sem ac, vestibulum placerat nisl. Duis
            aliquam pulvinar ligula at scelerisque. Nam dignissim placerat ipsum id hendrerit. Ut lobortis eu ex eu
            ullamcorper.
            Maecenas ullamcorper blandit mattis.</h2>
    </div>
</template>
  
<script setup lang="ts">
import { ref } from 'vue';

</script>
  
<style>
h2 {
    background: linear-gradient(90deg, black, transparent);
    background-size: 200%;
    animation: reveal both linear;
    animation-duration: 1ms;
    animation-timeline: view();
    background-repeat: no-repeat;
    animation-range: entry 40% cover 40%;
    background-clip: text;
    -webkit-background-clip: text;
    color: transparent;
}

@keyframes reveal {
    0% {
        background-position-x: 200%;
        transform: translateY(-100px)
    }

    100% {

        background-position-x: 0%;
        transform: translateY(0px)
    }
}
</style>
<script setup>
  import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcasts
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Parlons🍵" subTitle="Sujets divers..." />
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Voyage🏖✈" subTitle="Voyages culturels..." />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Beau temps☀⛱" subTitle="Pour rappeler le beau temps..." />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Montagnes à explorer⛰🚠" subTitle="Pour les amateurs d'escalade et de randonnées..." />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Radios populaires
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/120/300/300" title="Vibes Nocturnes🌙" subTitle="Pour accompagner tes nuits étoilées..." />
            <HomeCard image="https://picsum.photos/id/110/300/300" title="Feel Good Only😊" subTitle="Morceaux bonne humeur..." />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/221/300/300" title="Old but Gold🎶" subTitle="Intemporels traversant les générations..." />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/232/300/300" title="Rêveries Lunaires✨" subTitle="Une ambiance douce et planante pour s’évader..." />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/187/300/300" title="Farniente🌴" subTitle="Pour sentir la chaleur du soleil..." />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Musiques Recommandées
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/88/300/300" title="Deep Focus🎧" subTitle="Musique apaisante pour se concentrer..." />
            <HomeCard image="https://picsum.photos/id/243/300/300" title="Mystique🖤" subTitle="Des sons envoûtants et mystérieux..." />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/123/300/300" title="Sérénité🌧️" subTitle="Ces jours où on veut se poser..." />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/121/300/300" title="Éveil du Jour 🌄" subTitle="Partir sur le bon pied !" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/99/300/300" title="Western Dreams 🤠" subTitle="Saut dans le passé !" />
        </div>
    </div>
</template>
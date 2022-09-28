<template>
<nav>
    <v-navigation-drawer v-model="drawer" dark app mini-variant mini-variant-width="100" class="teal">
<v-list>
    <v-list-item class="mb-12">
        <v-list-item-content>
            <v-icon class="mb-2" large>fas fa-hand-holding-medical</v-icon>
            <v-list-item-subtitle justify-content-align="center">Medi</v-list-item-subtitle>
        </v-list-item-content>
    </v-list-item>
</v-list>
    </v-navigation-drawer>
</nav>
</template>

<script>
    export default{
        data: () =>({
            drawer: true
        })
    }
</script>
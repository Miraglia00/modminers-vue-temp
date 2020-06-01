<template>
<b-container>
    <b-row align-v="center" style="min-height:100vh" class="text-center">
        <b-col cols="12" offset="0" md="8" offset-md="2">
            <b-jumbotron border-variant="danger">
                <div>
                    <b-img center src="http://norpacking.hu/wp-content/uploads/2014/02/Under_Construction.png" width="200px" fluid alt="Responsive image"></b-img>
                </div>
                <template v-slot:header><h3 class="success">A weboldal jelenleg nem érhető el!</h3></template>

                <template v-slot:lead>
                    A folyamatos munkálatok miatt az oldal ideiglenesen nem érhető el. Megértésedet köszönjük.
                </template>

            </b-jumbotron>
        </b-col>
    </b-row>
</b-container>
</template>

<script>
export default {
}
</script>

<style>

</style>
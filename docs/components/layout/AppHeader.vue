<template>
    <div class="header">
        <div class="header-centered">
            <div class="header-logo">
                <img src="../../assets/logo.png" class="logo">
                <h1 class="header-title">
                    Vuex<span class="lighter">Forms</span>
                    <span class="version">v0.0.6 (alpha)</span>
                </h1>
            </div>
            <p class="slogan">
                A comprehensive form management solution for
                <a href="https://vuejs.org/">Vue.js</a>, built with
                <a href="https://vuex.vuejs.org/">Vuex</a> in mind.
            </p>
            <div class="features">
                <div class="columns">
                    <div class="column is-6">
                        <ul class="feature-list">
                            <li>Model based forms & validations</li>
                            <li>Use any data source to populate your forms</li>
                            <li>Dispatch form data via Vuex or AJAX</li>
                            <li>Loosely-coupled presentation system</li>
                            <li>Minimal logic required in components</li>
                            <li>Mixins for quick custom components</li>
                            <li>Easy to use input masking</li>
                            <li>Vuex NOT required</li>
                        </ul>
                    </div>
                    <div class="column is-6">
                        <ul class="feature-list">
                            <li>Robust validation, powered by <a
                                    href="https://monterail.github.io/vuelidate/">Vuelidate</a>
                            </li>
                            <li>Capable validation message system</li>
                            <li>Custom validation rules & messages</li>
                            <li>Localization for messages</li>
                            <li>Configurable validation behavior</li>
                            <li>Provides 28 validation rules out of the box (including Vuelidate's existing rules)</li>
                            <li>
                                Minimal dependencies
                                <br/>
                                <small>
                                    (<a href="https://monterail.github.io/vuelidate/">Vuelidate</a>,
                                    <a href="https://github.com/yeikos/js.merge">merge</a>)
                                </small>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="development-warning">
                    <a class="button" href="https://github.com/andycrockett/vuex-forms">View on Github</a>
                    <h2>
                        <em>Note</em>: This project is early in development.
                        <br/>
                        Documentation is not complete, but is actively being worked on.
                    </h2>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AppHeader'
    }
</script>
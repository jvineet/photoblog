<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-10">
                <div class="card card-default">
                    <div class="card-header">Example Component</div>

                    <div class="card-body">
                        <a href="https://www.accuweather.com/en/us/berkeley-ca/94704/weather-forecast/332044" class="aw-widget-legal">
                        </a><div id="awcc1518743080612" class="aw-widget-current"  data-locationkey="" data-unit="f" data-language="en-us" data-useip="true" data-uid="awcc1518743080612"></div>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
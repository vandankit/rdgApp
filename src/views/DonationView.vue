<template>
    <main>
        <section>
            <div class="row">
                <div class="card" style="height:auto">
                    <div class="card-body">
                        <h2 class="green-text mb-4">
                            Donate Now!
                        </h2>
                        <p class="card-description">
                            Choose the frequency of your donation
                        </p>
                        <div class="row">
                            <div class="form-radio ml-3">
                                <label class="form-check-label">
                                    <input type="radio" class="form-check-input" name="donation_frequency"
                                        id="recurring" value="monthly" required checked="true"> Monthly
                                    <i class="input-helper"></i></label>

                            </div>
                            <div class="form-radio ml-2">
                                <label class="form-check-label">
                                    <input type="radio" class="form-check-input" name="donation_frequency" id="one-time"
                                        value="one-time" required> One Time
                                    <i class="input-helper"></i></label>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

</template>
<style>
.form-check,
.form-radio {
    position: relative;
    display: block;
    margin-top: 15px;
    margin-bottom: 10px;
}
</style>
<script>

</script>